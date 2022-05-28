# Laravel Skill Test
This is an example application developed for an interview process

## Description
Create a very simple Laravel web application for task management: -Create task (info to save: task name, priority, timestamps) -Edit task -Delete task -Reorder tasks with drag and drop in the browser. Priority should automatically be updated based on this. #1 priority goes at top, #2 next down and so on. -Tasks should be saved to a mysql table.

BONUS POINT: add project functionality to the tasks. User should be able to select a project from a dropdown and only view tasks associated with that project.

You will be graded on how well-written & readable your code is, if it works, and if you did it the Laravel way.

## Installation

    Create a database locally named tasks (utf8_general_ci)
    Download composer https://getcomposer.org/download/
    check the .env file is present or rename env.example -> .env.
    Open the console and cd your project root directory
    Run composer install or php composer.phar install
    Run php artisan key:generate         //generate unique key
    Run php artisan migrate             //migrate tables yo db
    Run php artisan db:seed to run seeders, if any.
    Run php artisan serve

## You can now access yo

Please open localhost:8000 :)
