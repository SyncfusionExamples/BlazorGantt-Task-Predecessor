# Blazor Gantt Task Predecessor

This repository contains a Blazor Web Application that demonstrates the implementation of task predecessor relationships in the Syncfusion Blazor Gantt Chart. The sample focuses on defining and visualizing task dependencies within a project schedule.

## Project overview

The Syncfusion Blazor Gantt Chart provides built‑in support for task predecessor relationships, enabling you to represent dependencies between tasks in a project timeline. This project showcases how predecessor relationships such as **Finish-to-Start, Start-to-Start, Finish-to-Finish**, and **Start-to-Finish** are configured and rendered in a Blazor Web application.

The sample highlights how task dependencies influence scheduling behavior and timeline visualization. **Predecessor links** are displayed between tasks to clearly indicate execution order and dependency constraints. This functionality is essential for managing complex project schedules where tasks are interdependent.

The included demonstration provides a visual representation of predecessor links within the Gantt Chart and illustrates how changes in task scheduling reflect across dependent tasks.

## Features

- Configuration of task predecessor relationships
- Visualization of dependency links between Gantt Chart tasks
- Support for Finish-to-Start (FS), Start-to-Start (SS), Finish-to-Finish (FF), and Start-to-Finish (SF) predecessor types
- Automatic schedule updates based on task dependencies
- Implementation using Syncfusion Blazor Gantt Chart in a Blazor Web App application

## Prerequisites

- Visual Studio 2022 (or later)
- .NET SDK 8.0 or later
- Syncfusion Blazor Gantt NuGet package
- A valid Syncfusion license (Community or Trial)

## How to Run the Project

1. Clone or download this repository.
2. Open the project file (`.csproj`) in Visual Studio 2022 or later.
3. Restore the required NuGet packages.
4. Register your Syncfusion license key (if not already registered).
5. Build and run the application.
6. Navigate to the page hosting the Gantt Chart to view task predecessor relationships.

## Sample output

The following image illustrates task predecessor relationships rendered in the Gantt Chart:

<img width="1847" height="702" alt="image" src="https://github.com/user-attachments/assets/2e728f2f-6280-45ea-aac1-1e662b560f2b" />

## Syncfusion License

This sample uses the Syncfusion Blazor components, which require a valid Syncfusion license.

- Community License: https://www.syncfusion.com/products/communitylicense
- Trial License: https://www.syncfusion.com/account/manage-trials/start-trials

Ensure the license key is registered before running the application.