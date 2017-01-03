# Activating the assignments tab

To view and submit your assignments, you have to use the assignment tab on
the course JupyterHub server. The assignment tab is not activated by default.
You will have to manually activate it. To display the assignment tab,

1. Open a new terminal by clicking `New` in the upper right corner and
   selecting `Terminal`.
   ![](images/new_terminal.png)
2. In the terminal, type `nbgrader extension activate` and hit `Enter`. You
   should see 2 `OK`s and `Done.` in the last line of the output. If you see an
   error message, contact the TA.
   ![](images/nbgrader_extension_activate.png)
3. Click `Control Panel` in the upper right corner. Click `Stop My Server` and
   wait until the red button disappers. Restart your server by clicking
   `My Server`.
   ![](images/control_panel.png)
4. You should now be able to see the *Assignments* tab after _Files_,
   _Running_, and _Clusters_.
   ![](images/assignments_tab.png)

## Download and submit the assignments
1. When assignments are released, it will show up under `Released assignments`. 
   Click the blue `Fetch` button to download the assignments. 
   Downloading a new week's assignments will *NOT* affect your current week's assignments.
   ![](images/assignments_tab_first_assignment.png)
2. Once you have fetched the assignments, a folder named `WeekX_Assignment_due_XX_XX` will show up under `Downloaded assignments`.
   When you click that folder, you can see `Problem_1`, `Problem_2`, and `Problem_3`. 
   Those are the links to the assignment notebooks.
   After you completed your assignments, click the blue `Submit` button to submit your assignments. 
   All the assignment notebooks in that week's folder will be submitted at the same time.
  ![](images/submit_assignment.png)
3. You are allowed to submit an assignment *multiple* times. For example, if have
  already submitted an assignment but later realize you made a mistake and want
  to fix it, you can simply change your solution, save the notebook, and submit
  again. Your latest submission before deadline will be count as your final submission.
   ![](images/submitted_assignments.png) 

Notes:

- Remember that the assignments on GitHub are for reference only and you should
  use the course JupyterHub server to view, fetch, and submit your assignments.
- If you encounter any technical issues, please feel free to contact the
  instructors.

