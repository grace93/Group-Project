# Group-Project
using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace groupProject
{
    static class Program
    {
        /// <summary>
        /// The main entry point for the application.
        /// </summary>
        [STAThread]
        static void Main()
        {
            Application.EnableVisualStyles();
            Application.SetCompatibleTextRenderingDefault(false);
            Application.Run(new Form1());
        }

        

        class Person
        {
            public string name { get; protected set; }
            public string address { get; protected set; }
            public string dateOfBirth { get; protected set; }

        }

        class Employee : Person
        {
            public string username { get; protected set; }
            public string password { get; protected set; }
            public int priviledgeNumber { get; protected set; }

            public void Login()
            {

            }

            public void viewMembers()
            {

            }

            public void addMember()
            {

            }

            public void deleteMember()
            {

            }

            public void updateMember()
            {

            }
        }

        class Staff : Employee
        {
            public void ViewGames()
            {

            }

            public void ReserveGame()
            {

            }

            public void IssueGame()
            {

            }

            public void ProcessReturnedGames()
            {

            }

            public void GameAvailability()
            {

            }


        }

        class Manager : Employee
        {
            public void viewStaffMembers()
            {

            }

            public void addStaffMember()
            {

            }

            public void deleteStaffMember()
            {

            }

            public void updateStaffMember()
            {

            }

            public void ReportGameCatalogue()
            {

            }

            public void ReportOverdueGame()
            {

            }

            public void viewGame()
            {

            }

            public void addGame()
            {

            }

            public void deleteGame()
            {

            }

            public void updateGame()
            {

            }

            public void ReportAccountTransactions()
            {

            }

        }

        class Member : Person
        {

        }

        class Game
        {

        }

        class Transaction
        {

        }


    }
}
