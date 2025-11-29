<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Attendance - Clock In/Out</title>
    </head>
<body>

    <header>
        <h1>Employee Attendance System</h1>
    </header>

    <main>
        <section id="attendance-form-container">
            <h2>Clock In / Clock Out</h2>
            <p id="current-time-display">Current Time: <span id="time-placeholder">Loading...</span></p>

            <form id="attendance-form">
                
                <div class="form-group">
                    <label for="employee-id">Employee ID:</label>
                    <input type="text" id="employee-id" name="employeeId" placeholder="e.g., EMP101" required>
                </div>

                <div class="form-group">
                    <label for="action-type">Action:</label>
                    <select id="action-type" name="actionType" required>
                        <option value="">-- Select Action --</option>
                        <option value="clock-in">Clock In</option>
                        <option value="clock-out">Clock Out</option>
                        </select>
                </div>

                <button type="submit" id="submit-btn">Submit Attendance</button>
            </form>

            <div id="message-area" role="alert" aria-live="polite">
                </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Attendance System</p>
    </footer>

    </body>
</html>
