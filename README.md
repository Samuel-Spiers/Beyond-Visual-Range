# BVR - Beyond Visual Range
This is the repository that will be used for various testing phases of BVR.

--------------------------------------------------
### NOTE - EXTREMELY IMPORTANT: DUE TO THE USE OF GITHUB LFS, YOU MUST CLONE THE REPOSITORY FOR THE GAME TO WORK CORRECTLY WHEN DOWNLOADED. DO NOT DOWNLOAD THE ZIP FILE.
(This is due to zip compression causing issues with GitHub LFS file pointers resolving.)

To do this, follow the steps below:
 1. Install GitHub Desktop on your computer: [https://github.com/apps/desktop](https://github.com/apps/desktop)
 2. Click the <img width="66.6" height="30" alt="image" src="https://github.com/user-attachments/assets/0db44570-1fbc-48cf-ac32-c967c1e79067" /> button.
 3. Select "Open with GitHub Desktop"
 4. Set the "Local path" to where you want the game to be located. (including any future test versions)
 5. Click the "Clone" button.

This will download the game for you in a format that will work properly, as well as give you a desktop app to access future updates.

--------------------------------------------------

# FLIGHT TEST BUILD 1 IS LIVE
--------------------------------------------------
The first BVR flight physics test build is now live and available to all who have access to this repository!

If you find any issues, please create an issue in the "Issues" tab with a description of the problem, thanks.

For suggestions and/or to submit your custom physics settings, please fill out this [form](https://forms.gle/P2D4qjpB6gbGbR3i9).

***Please note: All assets/visuals are placeholders and WILL change in the future. This test is ONLY about the early flight physics.***

### In this test
--------------------------------------------------
You will have full access to the flight model physics variables in this version of the test.
These variables are explained below:
 - Lift Factor - The amount of lift produced by the forward movement of the aircraft. ***Default: 0.002***
 - Stall Speed - The true air speed in KM/H where the planew will enter a stall state. ***Default: 250***
 - Stall Force Multiplier - How strongly the stall effects aircraft movement, primarily pulling the nose down. ***Default: 1***
 - Roll Strength - Amount of force produced by the roll controls. ***Default: 1000***
 - Pitch Strength - Amount of force produced by the pitch controls. ***Default: 1000***
 - Yaw Strength - Amount of force produced by the yaw controls. ***Default: 500***
 - Slip Resistance - The aircraft's resistance to high angle of attack. Higher values mean a more "on rails" feel, lower values mean more slip or "drift". ***Default: 0.02***
 - Airbrake Strength - Direct multiplier of current aircraft drag. ***Default: 3***
 - Energy Loss Multiplier - Effects how much energy you lose for each degree of angle of attack. Higher values equal increased speed loss during high-G turns. ***Default: 50***

You can also modify fuel level on the fly, as well as game volume and camera sensitivity.

Finally, you have buttons to reset all settings to their defaults, as well as reset the plane to the starting position. NOTE: This does NOT reset anything else, including your current throttle setting.

--------------------------------------------------
## Happy Flying!
