# Space Shooter Add-ons

## Step 1: Spinoff

Log in to your pixelpad account and go to the below link

https://pixelpad.io/app/eleqtbozdlg/

You'll see a screen like the one below. Click Spinoff and name your game "[Your Name] Advanced Space Shooter"

![Spinoff Image](./images/spinoff.png)

You'll then click your game

## Bonus 1: Having the enemies fire back


### Step 1: Choose Enemy Laser Image
We will first choose the enemy laser image. 

Click the + next to Sprites

![Sprites Image](./images/sprites.png)

Click next until you get to the last screen and choose the blue laser image

![Blue Laser Imager](./images/blueLaser.png)

Name it `enemyLaser`

You should see something like this if you click on `enemyLaser.png` in the left pane:


![Enemy Laser Image](./images/enemyLaser.png)

### Step 2: Add the EnemyLaser Class

Click the + sign next to Classes

![Classes Image](./images/classes.png)

Name it `enemyLaser`

It should look like this:

![Enemy Laser](./images/enemyLaserClassInitial.png)


### Step 3: Fill out EnemyLaser Class

![Enemy Laser Mid](./images/enemyLaserMid.png)

### Step 4: Add Code to Enemy Class

![Enemy  Mid](./images/enemyMid.png)


### Step 5: Fix Laser Speed

You'll now see that the alien and the enemy go at the same speed and doesn't make the game more interesting. Let's fix the enemy laser speed.

![Enemy Laser Speed](./images/enemyLaserSpeed.png)

### Step 6: Make it so the player can destroy enemy lasers

To make the game even more interesting, let's make it so that the player can destroy the enemy laser with their laser. 

Go to the `Laser` class and add this code


![Updated Laser](./images/updatedLaser.png)


# Bonus 2: Adding Lives

### Step One: Add Heart Image

Go to sprites and add the heart image. Name it `heart`

## Step Two: Update Level One Code

Go to the `LevelOne` room and insert the following code

![Level One Lives](./images/levelOneLives.png)

Go to the `Player` loop code and update it to be the following:



## Step Three Fix the code

You will notice that if you play, that you still instantly die. This is because when the laser or enemy hits you, it keeps hitting you until you die. We need to set it up so that the laser or enemy can only hit you once. 

Update your `LevelOne` loop code to the following:

