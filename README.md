<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VETS CRM</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>VETS CRM</h1>
        <nav>
            <ul>
                <li><a href="#dashboard">Dashboard</a></li>
                <li><a href="#contacts">Contacts</a></li>
                <li><a href="#pipeline">Pipeline</a></li>
                <li><a href="#tasks">Tasks</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Dashboard Section -->
        <section id="dashboard" class="section">
            <h2>Dashboard</h2>
            <div class="widgets">
                <div class="widget">Total Clients: <span id="totalClients">0</span></div>
                <div class="widget">Total Leads: <span id="totalLeads">0</span></div>
                <div class="widget">Open Tasks: <span id="openTasks">0</span></div>
            </div>
        </section>

        <!-- Contacts Section -->
        <section id="contacts" class="section">
            <h2>Contact Management</h2>
            <form id="addContactForm">
                <input type="text" id="contactName" placeholder="Name" required>
                <input type="email" id="contactEmail" placeholder="Email" required>
                <input type="text" id="contactPhone" placeholder="Phone">
                <button type="submit">Add Contact</button>
            </form>
            <table id="contactsTable">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Email</th>
                        <th>Phone</th>
                        <th>Actions</th>
                    </tr>
                </thead>
                <tbody></tbody>
            </table>
        </section>

        <!-- Pipeline Section -->
        <section id="pipeline" class="section">
            <h2>Sales Pipeline</h2>
            <p>Feature under development...</p>
        </section>

        <!-- Tasks Section -->
        <section id="tasks" class="section">
            <h2>Task Management</h2>
            <form id="addTaskForm">
                <input type="text" id="taskTitle" placeholder="Task Title" required>
                <input type="date" id="taskDeadline" required>
                <button type="submit">Add Task</button>
            </form>
            <ul id="tasksList"></ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 VETS CRM by VoltEdge Tech Solutions</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
