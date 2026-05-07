# Conflict Resolution Explanation

During this assignment, I used a Git feature-branch workflow to manage two calculator features: multiplication and division. Each feature was developed independently on separate branches to avoid interference.

The multiplication branch implemented a multiply function with logging and updated the version to 1.1.0. The division branch implemented a divide function with a zero-division check and updated the version to 1.0.1.

A merge conflict occurred when both branches modified the same sections of code, including the version number and main execution block. I resolved this conflict manually by reviewing both versions, combining the required changes, and ensuring no functionality was lost.

The final version was set to 1.2.0, and I confirmed that all functions worked correctly after merging. This helped me understand how Git handles conflicts and the importance of careful manual resolution.