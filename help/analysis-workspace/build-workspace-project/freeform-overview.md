---
description: Overview of Workspace projects with menu bar and settings
keywords: Analysis Workspace
title: Projects overview
feature: CJA Workspace Basics
exl-id: 2eeb615c-57a1-4469-8d4a-8a61956bd6e6
---
# Projects overview

Workspace projects allow you to combine data components, tables and visualizations to craft your analysis and share with anyone in your organization. Before starting your first project, learn about how to access, navigate and manage your projects.  

## Project list {#project-list}

When you first go to **[!UICONTROL Analytics]** > **[!UICONTROL Workspace]**, the page lists all the projects you own or have been shared to you. This is also the landing page for Adobe Analytics, unless you have previously set a custom landing page. 

![](assets/sample-project.png)

The Workspace project list page contains the following information: 

|  Element  | Description  |
|---|---|
| [Create New Project](/help/analysis-workspace/home.md)  | Click this link to start a new project from scratch.  |
|  Manage Projects  |Clicking this link takes you to the Projects Component Manager ( **[!UICONTROL Analytics]** > **[!UICONTROL Components]** > **[!UICONTROL Projects]**), which lists all your projects and lets you tag, share, delete, rename, approve, copy, and export projects to CSV.  |
| Set as Landing Page | Turns this page into your Workspace landing page. |
|  [View Tutorials](/help/analysis-workspace/home.md)  |Takes you to the Analysis Workspace video tutorials.  |
|  Name  | Name of the Workspace project.  |
|  Owner  | The person who created this project (either you or someone who shared the project with you.)  |
| Type | Indicates whether this is a Workspace Project or a [Mobile Scorecard](/help/mobile-app/home.md). |
| [Project Role](/help/analysis-workspace/curate-share/share-projects.md) | Indicates your role for the project - owners, edit, duplicate, view. |
|  Tags  |Tags that were applied to the project.  |
|  Last Modified  | Date and time when the project was last modified.  |
| My Favorite Projects | To mark a project as a favorite, open the project and click the star next to its name. It will show up in this list the next time you open Workspace. |
| Frequently Viewed Projects | Lists all projects that you open frequently, for ease of access. |

## Menu bar {#menu-bar}

Within a project, the menu provides options for managing your project, adding components, finding help, and more. Each menu option can also be accessed by keyboard [shortcuts](/help/analysis-workspace/build-workspace-project/fa-shortcut-keys.md).

![](assets/menu.png)

|  Menu item  | Description  |
|---|---|
|  Project  | Includes common actions for project management, including New, Open, Save, Save As, and Save As template. You can also refresh the entire project to retrieve the most recent data and definitions by clicking Refresh Project. [Download CSV and PDF](/help/analysis-workspace/curate-share/download-send.md) options enable you to export data from Workspace. **Project Info & Settings** (see below) offers many options for managing your project.  |
|  Edit  | Undo or redo your last action. Clear All will reset your project to a blank starting point. |
|  Insert  | Insert new panels or visualizations from this menu. You can also insert new panels and visualizations from the left rail.  |
|  [Components](/help/components/overview.md)  | Create new filters, calculated metric, date range, or alert components from your project. You can also create new components from the left rail. If your component definitions have recently changed, Refresh Components will retrieve the latest definitions. |
|  [Share](/help/analysis-workspace/curate-share/send-schedule-files.md)  | Curate, share and schedule PDF/CSV projects to recipients in your organization.  |
|  Help  | Access help documentation, videos, and the Analytics [Experience League community](https://experienceleaguecommunities.adobe.com/t5/adobe-analytics/ct-p/adobe-analytics-community). Manage the visibility of Workspace tips as well as the [debugger](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md). Find details about Workspace and factors that impact project [performance](/help/analysis-workspace/workspace-faq/optimizing-performance.md).  |
|  Share button or Owner  | If you are in an Own or Edit for the project, the Share button in the top-right gives you one-click access to manage your project recipients. If you are in a Duplicate or View role for the project, you will see the project owner's name. |

### Project Info & Settings {#info-settings}

**[!UICONTROL Workspace]** > **[!UICONTROL Project]** > **[!UICONTROL Project Info & Settings]** provides project-level information on the currently active project.

![](assets/projectinfo.png)

Settings include:

|  Setting  | Description  |
|---|---|
|  Project Name  | The name given to the project. You can double-click the name to edit it.  |
|  Created By  | Project owner name  |
|  Last Modified  | Date of last modification to the project.  |
|  Tags  |Lists any tags applied to a project for easier categorization.  |
|  Description  | A description is useful for clarifying the purpose of a project. You can double-click the description to edit it.  |
|  Count repeat instances in project  | Specifies whether repeat instances are counted in reports. Note: this setting does not apply to Flow or Fallout visualizations.  |
|  [Project color palette](/help/analysis-workspace/build-workspace-project/color-palettes.md)  | You can change the categorical color palette used in Workspace, by choosing from out-of-the-box palettes that have been optimized for color blindness, or by specifying your custom palette. This feature affects many things in Workspace, including most visualizations.  |
| [View Density](/help/analysis-workspace/build-workspace-project/view-density.md) | Lets you see more data on the screen by reducing the vertical padding of the left rail, freeform tables and cohort tables. |

## Left rail {#left-rail}

Within a project, [panels](/help/analysis-workspace/c-panels/panels.md), tables, [visualizations](/help/analysis-workspace/visualizations/freeform-analysis-visualizations.md), and [components] are accessed from the left rail. These are your project building blocks.

You can also access visualizations and panels from the [Blank Panel](/help/analysis-workspace/c-panels/blank-panel.md) as well. 

Components (Dimensions, Metrics, Filters, Date Ranges) in the left rail relate to the active panel data view. The active panel will have a blue border around it, and the active data view will be listed at the top of the component rail.

![](assets/left-rail.png)

## Project canvas {#canvas}

The project canvas is where you bring together panels, tables, visualizations, and components to build your analysis. A project can contain many panels, and each panel can contain many tables and visualizations.

Panels are helpful when you want to organize your projects according to time periods, data views, or analysis use case. The active panel will have a blue border around it, and determines what components are available in the left rail.

Depending on the starting point you chose for your projects, you will either have a [freeform table](/help/analysis-workspace/visualizations/freeform-table/freeform-table.md) or a [blank panel](/help/analysis-workspace/c-panels/blank-panel.md) in the canvas to begin with. The quickest way to start analyzing is to select one or many components and simply drag & drop them into the project canvas. A table of data will automatically be rendered for you. [Learn more](/help/analysis-workspace/visualizations/freeform-table/freeform-table.md) about the different options for building a table, or leverage our [training tutorial](/help/analysis-workspace/home.md) for more guidance on building your first project.

![](assets/canvas.png)

## Project Manager {#manager}

Analysis Workspace projects can be managed under **Analytics > Components >  Projects**. The Project Manager shows the items that a specific user has created. Project ownership can be transferred to a new user under Admin > Analytics Users & Assets > Transfer Assets.

In the Projects Manager, you can add, tag, share, duplicate/copy, and more. Search for a project in the search bar or by using the filter options in the left rail. You can filter by tag, owners, project type and more.

![](assets/project-manager.png)

The following are common actions in the Projects manager, and can be taken on one or many projects at once:

|  Action  | Description  |
|---|---|
|  Add  | Create a new project from scratch.  |
|  Tag or Approve  | Choose “Tag” or “Approve” to organize your projects and make them easier to search for.  |
|  [Share](/help/analysis-workspace/curate-share/share-projects.md)  | Make a project available to other Analysis Workspace users in your organization.  |
|  Delete  | Delete your project.  |
|  Rename  | Edit the name of your project.  |
|  Copy  | Create a duplicate copy of your project. This creates a new project and project ID. Any shares or schedules tied to the original project will not be copied. |
|  Export to CSV  | Download your project as a CSV file, which includes plain-text data.  |
