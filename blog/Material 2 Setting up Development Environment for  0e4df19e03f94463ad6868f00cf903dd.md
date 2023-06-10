# Material 2: Setting up Development Environment for Flutter

Created by: Azraf Al Monzim
Created time: June 10, 2023 12:44 PM
Last edited by: Azraf Al Monzim
Last edited time: June 10, 2023 5:27 PM
Tags: Guides

## **Short Summary**

This blog provides a detailed guide on setting up a development environment for Flutter. From installing Git, GitHub CLI, OpenJDK, Flutter SDK, Visual Studio Code, and Android Studio, this comprehensive tutorial will help you set up all the necessary tools for Flutter development.

## **Details Blog**

Welcome to our guide on setting up a development environment for Flutter! In this tutorial, we will walk you through the step-by-step process of installing and configuring all the required tools to start building Flutter applications.

## **Prerequisites**

Before we dive into the setup process, make sure you have the following prerequisites installed on your system:

- Operating System: Windows (10 or later), macOS (Mojave or later), or Linux (64-bit)
- Disk Space: At least 6 GB  (excluding IDEs and additional dependencies)
- Tools: Git (version 2.x.x or later) and a text editor of your choice
- JDK: JDK version 11+

## **Step 1: Install Git**

1. Download Git from the official website: **[https://git-scm.com/downloads](https://git-scm.com/downloads)**.
2. Run the installer and follow the on-screen instructions to complete the installation. [Install with Default Settings]

![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled.png)

## **Step 2: Install GitHub CLI**

1. Visit the GitHub CLI repository on GitHub: [https://cli.github.com](https://cli.github.com/)
2. Download and intall with default settings

![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%201.png)

## **Step 3: Install OpenJDK**

1. Visit the AdoptOpenJDK website: [https://learn.microsoft.com/en-us/java/openjdk/download](https://learn.microsoft.com/en-us/java/openjdk/download)
2. Select your preferred version of OpenJDK and download the installer for your operating system.
3. Run the installer and follow the on-screen instructions to complete the installation.

![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%202.png)

## **Step 4: Install Flutter SDK**

1. Visit the official Flutter website at [https://docs.flutter.dev/get-started/install/windows#windows-setup](https://docs.flutter.dev/get-started/install/windows#windows-setup) and click on the "Get Started" button.
2. Download the Flutter SDK for your operating system.
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%203.png)
    
3. Extract the downloaded file to a location of your choice. For example, **`C:\src\flutter`** on Windows or **`/Users/your_username/flutter`** on macOS/Linux.
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%204.png)
    
4. Add the Flutter SDK's **`bin`** directory to your system's PATH variable. This step allows you to access Flutter commands from any directory in the command line.
    - On Windows: Open the Environment Variables settings, find the "Path" variable, and append **`C:\src\flutter\bin`** to it.
        
        ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%205.png)
        
        ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%206.png)
        
        ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%207.png)
        
    - On macOS/Linux: Open the terminal and run the following command, replacing **`your_username`** with your actual username:
        
        ```bash
        export PATH="$PATH:/Users/your_username/flutter/bin"
        ```
        
5. Verify the installation by opening a new terminal or command prompt and running **`flutter doctor`**  . This command checks for any necessary dependencies and provides recommendations if anything is missing.
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%208.png)
    

## **Step 5: Install Visual Studio Code**

1. Download Visual Studio Code from the official website: [https://code.visualstudio.com/](https://code.visualstudio.com/)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%209.png)
    
2. Run the installer and follow the on-screen instructions to complete the installation.
3. Open Visual Studio Code and install the Flutter and Dart extensions by searching for them in the Extensions panel (Ctrl+Shift+X).
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2010.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2011.png)
    

## **Step 6: Install Android Studio**

1. Download Android Studio from the official website: **[https://developer.android.com/studio](https://developer.android.com/studio)**.
2. Run the installer and follow the on-screen instructions to complete the installation.
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2012.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2013.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2014.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2015.png)
    
3. During the installation, make sure to select the Flutter and Dart plugins.
4. Run this command `flutter doctor` 
5. Then accept run this command `flutter doctor --android-licenses`
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2016.png)
    
6. Then run this `flutter doctor`  again
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2017.png)
    

## Step 6.1: Create a android Simulator

1. Open android Studio and open Virtual Device manager
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2018.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2019.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2020.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2021.png)
    
    ![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2022.png)
    

## **Step 7: Configure IDE**

After installing your preferred IDE, open it and configure it to work with Flutter:

1. Open the IDE's settings/preferences and navigate to the Flutter section.
2. Set the Flutter SDK path to the location where you extracted the Flutter SDK in Step 1.
3. Apply the changes and restart the IDE for the settings to take effect.

## **Step 8: Create a New Flutter Project**

Now that we have everything set up, let's create a new Flutter project:

1. Open your terminal or command prompt and navigate to the directory where you want to create the project.
2. Run the following command to create a new Flutter project:Replace **`my_app`** with the desired name of your project.
    
    ```bash
    flutter create my_app
    ```
    

## **Step 9: Run Your First Flutter App**

1. In your terminal or command prompt, navigate to the project directory (**`my_app`** in this example).
2. Connect an Android or iOS device to your computer or set up an emulator/simulator.
3. Run the following command to launch your app on the connected device/emulator:If everything is set up correctly, you should see your app running on the device/emulator.
    
    ```bash
    flutter run
    ```
    

![Untitled](Material%202%20Setting%20up%20Development%20Environment%20for%20%200e4df19e03f94463ad6868f00cf903dd/Untitled%2023.png)

Congratulations! You have successfully set up your development environment for Flutter and created your first Flutter app. Now you can start exploring Flutter's rich set of features and building incredible cross-platform mobile applications.

Remember to refer to the official Flutter documentation and community resources for further learning and support on your Flutter development journey. Happy coding!

## **Conclusion**

Congratulations! You have successfully set up your development environment for Flutter. You installed Git, GitHub CLI, OpenJDK, Flutter SDK, Visual Studio Code, and Android Studio, which are essential tools for Flutter development. You are now ready to create amazing cross-platform mobile applications using Flutter.

Remember to refer to the official Flutter documentation and community resources for further learning and support on your Flutter development journey. Happy coding!