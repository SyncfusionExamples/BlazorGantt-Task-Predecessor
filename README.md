# Blazor Gantt Task Predecessor

This repository contains a Blazor Server sample that demonstrates the implementation of task predecessor relationships in the Syncfusion Blazor Gantt Chart. The sample focuses on defining and visualizing task dependencies within a project schedule.

## Project Overview

The Syncfusion Blazor Gantt Chart supports task predecessor functionality to represent dependencies between tasks in a project timeline. This project showcases how predecessor relationships such as Finish-to-Start, Start-to-Start, Finish-to-Finish, and Start-to-Finish are configured and rendered in a Blazor Server application.

The sample highlights how task dependencies influence scheduling behavior and timeline visualization. Predecessor links are displayed between tasks to clearly indicate execution order and dependency constraints. This functionality is essential for managing complex project schedules where tasks are interdependent.

The included demonstration provides a visual representation of predecessor links within the Gantt Chart and illustrates how changes in task scheduling reflect across dependent tasks.

## Features

- Configuration of task predecessor relationships
- Visualization of dependency links between Gantt tasks
- Support for Finish-to-Start (FS), Start-to-Start (SS), Finish-to-Finish (FF), and Start-to-Finish (SF) predecessor types
- Automatic schedule updates based on task dependencies
- Implementation using Syncfusion Blazor Gantt in a Blazor Server application

## Prerequisites

- Visual Studio 2022 (v17.8 or later)
- .NET 8 SDK with Blazor Server support
- Syncfusion Blazor Gantt NuGet package

## How to Run the Project

1. Clone or download this repository.
2. Open the solution in Visual Studio 2022 (v17.8 or later).
3. Restore NuGet packages.
4. Register your Syncfusion license key (if not already registered).
5. Run the application.

## Sample Output

The following image illustrates task predecessor relationships rendered in the Gantt Chart:

<img width="1847" height="702" alt="image" src="https://github.com/user-attachments/assets/2e728f2f-6280-45ea-aac1-1e662b560f2b" />

## Syncfusion License

This sample uses the Syncfusion Blazor components, which require a valid Syncfusion license.

- Community License: https://www.syncfusion.com/products/communitylicense
- Trial License: https://www.syncfusion.com/account/manage-trials/start-trials

Ensure the license key is registered before running the application.