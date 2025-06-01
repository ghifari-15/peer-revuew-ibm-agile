Title: [BUG] - Due date not saved after editing task
Labels: bug
Assignees: ''

Bug Description:
When I try to edit an existing task to change its due date, the date change is not saved. After saving, the due date reverts to the original date before editing.

Steps to Reproduce:

Go to the task list page.
Create a new task with the description "Test Edit Date" and due date '2025-06-10'.
Save the task. Ensure the task appears with the correct date.
Click on the "Test Edit Date" task to open it in edit mode.
Change the due date field to '2025-06-12'.
Click the "Save Changes" button.
Observe the displayed due date for the "Test Edit Date" task in the task list.
Expected Behavior:
The due date for the "Test Edit Date" task should change and display '2025-06-12'.

Actual Behavior:
The due date for the "Test Edit Date" task still displays '2025-06-10', unchanged by the edit.
