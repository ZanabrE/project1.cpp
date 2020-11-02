//This program will have 10 multiple questions for a quiz
//will calculate the correct answers and display it.
//Ernesto L Zanabria 10/24/2020

#include <iostream>
#include <iomanip>
#include <string>
#include <fstream>
using namespace std;

int main() 
{
    //Constants for the questions 1 to 10.
    const int MIN_NUM = 1,
              MAX_NUM = 10;

    //Constant for the choices 1 to 4.
    const int iPHONE = 1,
              PLAY_STATION_5 = 2,
              TESLA = 3,
              CLOUD_COMPUTING = 4;
    
    //Variables.
    int correctAnswer;          //To hold correct answers.
    int incorrectAnswer;        //To hold wrong answers.
    int choice;                 //Menu choice.
    int model;                  //To hold model.                        
    int answer;                 //To hold the answer.
    double score;               //To hold score.
    double total;               //To hold total.   
    double percentage;          //Calculating the percentage.

    char again;                 //To hold the Y or N input.

    do
    {
        //Displaying the table options.
        cout << "-------------------------------------------------\n";
        cout << "\tTECHNOLOGY AND THEIR CREATIONS\t\n";
        cout << "-------------------------------------------------\n";
        cout << "1. iPHONE\n"
             << "2. PLAY STATION\n"
             << "3. TESLA\n"
             << "4. CLOUD COMPUTING\n"
             << "Enter your choice: ";
        cin >> choice;
        
        //Validate the table options.
        while (choice < iPHONE || choice > CLOUD_COMPUTING)
        {
            cout << "Please, enter one of the options: ";
            cin >> choice;
        }

        //Process the user's choice for the iPHONE 12.
        if (choice == iPHONE)
        {
            //Displaying the header for the iPHONE 12.
            cout << "-------------------------------------------------\n";
            cout << "\t\tiPHONE 12 FEATURES\t\n";
            cout << "-------------------------------------------------\n";
            //Displaying question 1 and their choices.
            cout << "1). Which iPHONE 12 will support wireless charging? \n"
                 << "1. iPHONE 12 mini.\n"
                 << "2. iPHONE 12.\n"
                 << "3. iPHONE 12 PRO/MAX.\n"
                 << "4. All of the above.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond to the user's selection question 1.
            switch (answer)
            {
                case 1:
                    cout << "That's incorrect.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's incorrect.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's incorrect.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            
            cout << "-------------------------------------------------\n";

            //Displaying question 2 and the choices.
            cout << "2). What is the price of the iPHONE 12 mini and display? \n"
                 << "1. $499 with 4.9 inches display.\n"
                 << "2. $699 with 5.4 inches display.\n"
                 << "3. $599 with 5.1 inches display.\n"
                 << "4. $799 with 6.1 inches display.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond to the user's selection for question 2.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 3 and the choices.
            cout << "3). What does the design of iPHONE 12 resemble to?\n"
                 << "1. iPHONE 4.\n"
                 << "2. iPHONE 5.\n"
                 << "3. iPHONE 6.\n"
                 << "4. iPhone 7.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond to the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3: 
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 4 and the choices.
            cout << "4). What new component connectivity the iPHONE 12 will have?\n"
                 << "1. 4G modem and 4G antenna that support sub-5GHz.\n"
                 << "2. 3G modem and 3G antenna that support sub-4GHz.\n"
                 << "3. 5G modem and 5G antenna that support sub-6GHz.\n"
                 << "4. 2G modem and 2G antenna that support sub-3GHz.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond to the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Thats not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 5 and the choices.
            cout << "5). What new processor the iPHONE 12 will have?\n"
                 << "1. A14 Bionic.\n"
                 << "2. A13 Bionic.\n"
                 << "3. A12 Bionic.\n"
                 << "4. A11 Bionic.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 6 and the choices.
            cout << "6). Which iPHONE 12 will support Night Mode photography\n"
                 << "    and a new sensor-shift optical image stabilization\n"
                 << "    system for each camera?\n"
                 << "1. iPHONE 12 mini.\n"
                 << "2. All of the iPHONE 12.\n"
                 << "3. iPHONE 12.\n"
                 << "4. iPHONE 12 PRO/MAX.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    cout << "Please choose the right answer.\n";
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 7 and the choices.
            cout << "7). Which iPHONE 12 will come with LiDAR Scanner?\n"
                 << "1. iPHONE 12.\n"
                 << "2. NONE.\n"
                 << "3. iPHONE 12 PRO/MAX.\n"
                 << "4. iPHONE 12 mini.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 8 and the choices.
            cout << "8). What is storage range of the iPHONE 12 PRO MAX?\n"
                 << "1. 128GB to 256GB.\n"
                 << "2. 64GB to 128GB.\n"
                 << "3. 256GB to 512GB.\n"
                 << "4. 128GB to 512GB.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout<< "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 9 and the choices.
            cout << "9). Which iPHONE 12 model feature OLED Super Retina\n"
                 << "    XDR display?\n"
                 << "1. All iPHONE 12 models.\n"
                 << "2. iPHONE 12 mini models.\n"
                 << "3. iPHONE 12 models.\n"
                 << "4. iPHONE 12 PRO/MAX models.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
            case 1:
                cout << "Correct!\n";
                correctAnswer ++;
                break;
            case 2:
                cout << "That's not correct.\n";
                incorrectAnswer ++;
                break;
            case 3:
                cout << "That's not correct.\n";
                incorrectAnswer ++;
                break;
            case 4:
                cout << "That's not correct.\n";
                incorrectAnswer ++;
                break;
            default:
                break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 10 and the choices.
            cout << "10). Which Appel's 2020 iPHONE lineup has the smallest\n"
                 << "     display?\n"
                 << "1. iPHONE X.\n"
                 << "2. iPHONE XS.\n"
                 << "3. iPHONE 12 mini.\n"
                 << "4. iPHONE 11.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

        }

        //Process the user's choice for PLAY STATION 5.
        if (choice == PLAY_STATION_5)
        {
            //Displaying the header for PLAY STATION 5.
            cout << "-------------------------------------------------\n";
            cout << "        PLAY STATTION 5 SPECIFICATIONS\n";
            cout << "-------------------------------------------------\n";
            //Displaying questions 1 and their choices.
            cout << "1). What CPU is inside PLAY STATION 5?\n"
                 << "1. x86-64-AMD Ryzen™ 'Zen 1' 4 Cores/8 Threads Variable\n"
                 << "   frequency, up to 3.5 GHz.\n"
                 << "2. x86-64-AMD Ryzen™ 'Zen 3' 12 Cores/20 Threads Variable\n"
                 << "   frequency, up to 3.5 GHz.\n"
                 << "3. x86-64-AMD Ryzen™ 'Zen 2' 8 Cores/16 Threads Variable\n"
                 << "   frequency, up to 3.5 GHz.\n"
                 << "4. x86-64-AMD Ryzen™ 'Zen 4' 14 Cores/24 Threads Variable\n"
                 << "   frequency, up to 3.5 GHz.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 2 and their choices.
            cout << "2). What GPU is inside PLAY STATION 5?\n"
                 << "1. AMD Radeon™ RDNA 2-based graphics engine Ray Tracing\n"
                 << "   Acceleration Variable frequency, up to 2.23 GHz (10.3 TFLOPS).\n"
                 << "2. AMD Radeon™ RDNA 4-based graphics engine Ray Tracing\n"
                 << "   Acceleration Variable frequency, up to 4.43 GHz (12.3 TFLOPS).\n"
                 << "3. AMD Radeon™ RDNA 1-based graphics engine Ray Tracing\n"
                 << "   Acceleration Variable frequency, up to 1.23 GHz (4.3 TFLOPS).\n"
                 << "4. AMD Radeon™ RDNA 3-based graphics engine Ray Tracing\n"
                 << "   Acceleration Variable frequency, up to 3.23 GHz (8.3 TFLOPS).\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 3 and their choices.
            cout << "3). The System Memory in PLAY STATION 5 will have?\n"
                 << "1. GDDR6 4GB 448GB/s Bandwidth.\n"
                 << "2. GDDR6 12GB 448GB/s Bandwidth.\n"
                 << "3. GDDR6 8GB 448GB/s Bandwidth.\n"
                 << "4. GDDR6 16GB 448GB/s Bandwidth.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user's selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 4 and their choices.
            cout << "4). How much capacity will have the SSD in\n"
                 << "    PLAY STATION 5?\n"
                 << "1. 512GB 4.5GB/s Read Bandwidth (Raw).\n"
                 << "2. 1000GB 6.5GB/s Read Bandwidth (Raw(.\n"
                 << "3. 825GB 5.5GB/s Read Bandwidth (Raw).\n"
                 << "4. 650GB 5.0GB/s Read Bandwidth (Raw).\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 5 and their choices.
            cout << "5). What is the Optical Drive in PLAY STATION 5?\n"
                 << "1. Ultra HD Blu-ray (44G/60G) ~4xCAVBD-ROM(12G/24G) ~2xCAVBD-R/RE\n"
                 << "   (12G/24G) ~2xCAVDVD ~3.2xCLV.\n"
                 << "2. Utra HD Blu-ray (66G/100G) ~10xCAVBD-ROM(25G/50G) ~8xCAVBD-R/RE\n"
                 << "   (25G/50G) ~8xCAVDVD ~3.2xCLV.\n"
                 << "3. Ultra HD Blu-ray (55G/80G) ~8xCAVBD-ROM(18G/36G) ~4xCAVBD-R/RE\n"
                 << "   (18G/36G) ~4xCAVDVD ~3.2xCLV.\n"
                 << "4. Ultra HD Blu-ray (48G/70G) ~6xCAVBD-ROM(18G/24G) ~6xCAVBD-R/RE\n"
                 << "   (18G/24G) ~6xCAVDVD ~3.2xCLV.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 6 and their choices.
            cout << "6). Which PLAY STATION 5 Game Disc can be insert?\n"
                 << "1. Ultra HD Blu-ray, up to 100GB/disc.\n"
                 << "2. Ultra HD Blu-ray, up to 60GB/disc.\n"
                 << "3. Ultra HD Blu-ray, up to 80GB/disc.\n"
                 << "4. Ultra HD Blu-ray, up to 120GB/disc.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 7 and their choices.
            cout << "7). Which will be the Video Out port in PLAY STATION 5?\n"
                 << "1. HDMI™ OUT port Support of 1080p TVs.\n"
                 << "2. HDMI™ OUT port Support of HD 1080p TVs.\n"
                 << "3. HDMI™ OUT port Support of HD 1080p 4K TVs.\n"
                 << "4. HDMI™ OUT port Support of 4K 120Hz TVs, 8K TVs, VRR\n"
                 << "   (specified by HDMI ver.2.1)\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 8 and their choices.
            cout << "8). Which will be the Audio in PLAY STATION 5?\n"
                 << "1. Dolby Atmos.\n"
                 << "2. Tempest 3D AudioTech.\n"
                 << "3. Surround Sound Dolby Atmos.\n"
                 << "4. Digital Surround Sound.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 9 and their choices.
            cout << "9). What is the Input/Output on PLAY STATION 5?\n"
                 << "1. Super-Speed USB(USB 3.1 Gen1) port x 2 AUX port x 1.\n"
                 << "2. USB Type-A port(Hi-Speed USB)USB Type-A port(Super-Speed\n"
                 << "   USB 10Gbps) x2 USB Type-C® port (Super-Speed USB 10Gbps).\n"
                 << "3. Super-Speed USB(USB 3.1 Gen.1) port x 3 AUX port x 1.\n"
                 << "4. All of the above.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 10 and ther choices.
            cout << "10). What Networking PLAY STATION 5 will have inside?\n"
                 << "1. Ethernet(10BASE-T, 100BASE-TX, 1000BASE-T) x1 IEEE 802.11\n"
                 << "   a/b/g/n/ac Bluetooth® 4.0(LE).\n"
                 << "2. Ethernet(10BASE-T, 100BASE-TX, 1000BASE-T) x1 IEEE 802.11\n"
                 << "   a/b/g/n/ac Bluetooth®v4.0.\n"
                 << "3. Ethernet(10BASE-T, 100BASE-TX, 1000BASE-T)IEEE 802.11\n"
                 << "   a/b/g/n/ac/axBluethooth® 5.1.\n"
                 << "4. NONE.\n"
                 << "Choose you answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

        }

        //Process the user's choice for TESLA.
        if (choice == TESLA)
        {
            //Displaying the header for TESLA choice.
            cout << "-------------------------------------------------\n";
            cout << "      TESLA MODEL X SPECIFICATIONS/FEATURE\n";
            cout << "-------------------------------------------------\n";
            //Displaying question 1 and their choices.
            cout << "1). What options TESLA MODEL X will have for Safety\n"
                 << "   and Security?\n"
                 << "1. Front and rear ventilated disc brakes.\n"
                 << "2. Dual front impact airbags.\n"
                 << "3. Remote keyless entry.\n"
                 << "4. All of the above.\n"
                 << "Choose you answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 2 and their choices.
            cout << "2). Which is the Standard Engine of TESLA MODEL X?\n"
                 << "1. Engine (electric).\n"
                 << "2. Engine (electric) and fuel.\n"
                 << "3. Engine v6 Dual Valve.\n"
                 << "4. Engine v4 Dual Valve.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 3 and their choices.
            cout << "3). How many miles the Model X Long Range will cover with a\n"
                 << "    fully battery charged?\n"
                 << "1. 435 miles.\n"
                 << "2. 555 miles.\n"
                 << "3. 328 miles.\n"
                 << "4. 485 miles.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 4 and their choices.
            cout << "4). How many miles the Model X Performance will cover with a\n"
                 << "    fully charged battery?\n"
                 << "1. 328 miles.\n"
                 << "2. 305 miles.\n"
                 << "3. 312 miles.\n"
                 << "4. 319 miles.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 5 with their choices.
            cout << "5). The Tesla Model X will come with a transmission of?\n"
                 << "1. Automatic 7 Speed Transmission.\n"
                 << "2. Automatic 8 Speed Transmission.\n"
                 << "3. Automatic 1 Speed Transmission.\n"
                 << "4. Automatic 6 Speed Transmission.\n"
                 << "Choose your asnwer: ";   
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";
            
            //Displaying question 6 with their choices.
            cout << "6). On Tesla Model X will come with what Drivetrain options?\n"
                 << "1. Front Wheel Drive.\n"
                 << "2. All Wheel Drive.\n"
                 << "3. Rear Wheel Drive.\n"
                 << "4. NONE.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 7 and their choices.
            cout << "7). The Tesla Model X dashboard will have?\n"
                 << "1. 17-inch Touch Screen/Navigation System.\n"
                 << "2. Bluetooth/USBports/Satellite Radio/HD Radio.\n"
                 << "3. 17-Speaker Stereo/Wi-Fi Hot Spot/Smartphone\n"
                 << "   charging pad, and Keyless Entry\n"
                 << "4. All of the options.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 8 and their options.
            cout << "8). How much MPG the Tesla Model X Long Range provided?\n"
                 << "1. 99 City, 93 Highway, and 96 MPGe combined.\n"
                 << "2. 88 City, 81 Highway, and 83 MPGe combined.\n"
                 << "3. 91 City, 89 Highway, and 90 MPGe combined.\n"
                 << "4. 96 City, 90 Highway, and 91 MPGe combined.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 9 and their options.
            cout << "9). What functionalities can do with Autopilot on a Tesla Vehicle?\n"
                 << "1. Navigate on Autopilot.\n"
                 << "2. Summon (Automatically retrive your car).\n"
                 << "3. All of these functionalities.\n"
                 << "4. Autopark (Parallel and perpendicular parking).\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 10 and their options.
            cout << "10). What is the maximum passenger and cargo capacity\n"
                 << "     of the Tesla Model X?\n"
                 << "1. 5 passengers.\n"
                 << "2. 7 passengers.\n"
                 << "3. 6 passengers.\n"
                 << "4. 4 passengers.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

        }

        //Process the user's choice for CLOUD COMPUTING.
        if (choice == CLOUD_COMPUTING)
        {
            //Displaying the header for CLOUD COMPUTING choice.
            cout << "-------------------------------------------------\n";
            cout << "        CLOUD COMPUTING AND ITS BENEFITS\n";
            cout << "-------------------------------------------------\n";
            //Displaying question 1 and their choices.
            cout << "1). What are the services can CLOUD COMPUTING provide?\n"
                 << "1. All of the services.\n"
                 << "2. Server/Storage.\n"
                 << "3. Databases/Networking.\n"
                 << "4. Software/Analytics/Intelligence.\n"
                 << "Choose your anser: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 2 and their choices.
            cout << "2). What are the benefits of CLOUD COMPUTING?\n"
                 << "1. Cost/Speed/Global Scale.\n"
                 << "2. Productivity/Performance/Reliability/Security\n"
                 << "3. All of the options.\n"
                 << "4. 1 or 2.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 3 and their choices.
            cout << "3). How services of CLOUD COMPUTING can be provide?\n"
                 << "1. Public/Private Cloud.\n"
                 << "2. Public/Private/Hybrid Cloud.\n"
                 << "3. Hybrid/Private Cloud.\n"
                 << "4. Hybrid/Public Cloud.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 4 and their choices.
            cout << "4). Who owns Public Clouds and their Operations?\n"
                 << "1. An Individual.\n"
                 << "2. Anyone that purchases.\n"
                 << "3. The Government (Russia/China probably possible).\n"
                 << "4. Third-party (Microsoft Azure).\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 5 and their choices.
            cout << "5). What is Private Cloud Computing?\n"
                 << "1. Can share resources with others.\n"
                 << "2. Internal Network (Internal use only).\n"
                 << "3. Not Secure.\n"
                 << "4. Anyone can access it.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 6 and their choices.
            cout << "6). What is Hybrid Cloud Computing?\n"
                 << "1. Combines Private and Public Cloud.\n"
                 << "2. Can share only data to individual.\n"
                 << "3. It is not flexible.\n"
                 << "4. You cannot move data between two environments.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 7 and their choices.
            cout << "7). The types of Computing Cloud are?\n"
                 << "1. IaaS.\n"
                 << "2. PaaS.\n"
                 << "3. AaaS.\n"
                 << "4. All of the above.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 8 and their choices.
            cout << "8). What IaaS stands for?\n"
                 << "1. Infrastructure as a Station.\n"
                 << "2. Infrastructure as a Server.\n"
                 << "3. Infrastructure as a Service.\n"
                 << "4. Infrastructure as a Software.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 9 and their choices.
            cout << "9). What PaaS stands for?\n"
                 << "1. Platform as a Service.\n"
                 << "2. Platform as a Software.\n"
                 << "3. Platform as a Server.\n"
                 << "4. Platform as a Station.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

            //Displaying question 10 and their choices.
            cout << "10). What SaaS stands for?\n"
                 << "1. Software as a Server.\n"
                 << "2. Software as a Software.\n"
                 << "3. Software as a Service.\n"
                 << "4. Software as a Station.\n"
                 << "Choose your answer: ";
            cin >> answer;
            cout << "-------------------------------------------------\n";

            //Validate the correct answer.
            while (answer < 1 || answer > 4)
            {
                cout << "Please choose the right option.\n";
                cout << "Choose your answer: ";
                cin >> answer;
            }

            //Respond the user selection.
            switch (answer)
            {
                case 1:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 2:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                case 3:
                    cout << "Correct!\n";
                    correctAnswer ++;
                    break;
                case 4:
                    cout << "That's not correct.\n";
                    incorrectAnswer ++;
                    break;
                default:
                    break;
            }
            cout << "-------------------------------------------------\n";

        }

        double score = 0;   //Initialize the accumulator.
        for (int count = 0; count <= correctAnswer; count++)
        {
            score += correctAnswer;
        }
        
        //Calculations for correct answers and their percentage.
        score = correctAnswer * 10;
        total = score / 100;
        percentage = total * 100;

        //Displaying the result.
        cout << "The number correct answered is: " << correctAnswer << "\n";
        cout << "The total score of correct answered is: " << score << "\n";
        cout << "and the percentage of correct answered is: " << percentage << "⁒\n";
        cout << "-------------------------------------------------\n";
        
        //Validate the score to re-take the quiz.
        if (score >= 70 || score < 79)
        {
            cout << "Do you want to take the quiz again? (Y/N): ";
            cin >> again;
        }
        cout << "-------------------------------------------------\n";
    } while (score >= 80);

    return 0;
}
