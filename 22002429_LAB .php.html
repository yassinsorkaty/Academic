<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GPA Calculator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        table {
            width: 50%;
            margin: 50px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #000;
        }
        select {
            width: 100%;
            padding: 5px;
        }
        input[type="submit"], input[type="reset"] {
            padding: 8px 20px;
            margin-top: 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<h2>GPA Calculator</h2>

<form id="gpaForm">
    <table>
        <tr>
            <th>Course Code</th>
            <th>Credit Hours</th>
            <th>Grade</th>
        </tr>
        <!-- Six Course Inputs -->
        <tr>
            <td><input type="text" name="course1" placeholder="Course Code"></td>
            <td><input type="number" name="credit1" placeholder="Credit Hours"></td>
            <td>
                <select name="grade1">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <td><input type="text" name="course2" placeholder="Course Code"></td>
            <td><input type="number" name="credit2" placeholder="Credit Hours"></td>
            <td>
                <select name="grade2">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <td><input type="text" name="course3" placeholder="Course Code"></td>
            <td><input type="number" name="credit3" placeholder="Credit Hours"></td>
            <td>
                <select name="grade3">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <td><input type="text" name="course4" placeholder="Course Code"></td>
            <td><input type="number" name="credit4" placeholder="Credit Hours"></td>
            <td>
                <select name="grade4">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <td><input type="text" name="course5" placeholder="Course Code"></td>
            <td><input type="number" name="credit5" placeholder="Credit Hours"></td>
            <td>
                <select name="grade5">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <td><input type="text" name="course6" placeholder="Course Code"></td>
            <td><input type="number" name="credit6" placeholder="Credit Hours"></td>
            <td>
                <select name="grade6">
                    <option value="4.00">A</option>
                    <option value="3.75">A-</option>
                    <option value="3.50">B+</option>
                    <option value="3.00">B</option>
                    <option value="2.50">C+</option>
                    <option value="2.00">C</option>
                    <option value="1.50">D+</option>
                    <option value="1.00">D</option>
                    <option value="0.00">F</option>
                </select>
            </td>
        </tr>
        <tr>
            <th>Total Hours</th>
            <td colspan="2"><span id="totalHours">0</span></td>
        </tr>
        <tr>
            <th>Current CGPA</th>
            <td colspan="2"><input type="text" id="pastCgpa" placeholder="Past CGPA"></td>
        </tr>
        <tr>
            <th>Total Credits Taken</th>
            <td colspan="2"><input type="number" id="pastCredits" placeholder="Total Credits"></td>
        </tr>
        <tr>
            <th>Current Semester GPA</th>
            <td colspan="2"><span id="currentGPA">0.00</span></td>
        </tr>
        <tr>
            <th>New CGPA</th>
            <td colspan="2"><span id="newCGPA">0.00</span></td>
        </tr>
        <tr>
            <td colspan="3">
                <input type="submit" value="Calculate">
                <input type="reset" value="Reset">
            </td>
        </tr>
    </table>
</form>

<script>
    document.getElementById('gpaForm').addEventListener('submit', function(event) {
        event.preventDefault();
        let totalCredits = 0;
        let totalGradePoints = 0;

        // Calculate current semester GPA
        for (let i = 1; i <= 6; i++) {
            const credit = parseFloat(document.getElementsByName('credit' + i)[0].value);
            const grade = parseFloat(document.getElementsByName('grade' + i)[0].value);
            if (!isNaN(credit) && !isNaN(grade)) {
                totalCredits += credit;
                totalGradePoints += credit * grade;
            }
        }

        // Calculate current semester GPA
        const currentGPA = (totalGradePoints / totalCredits).toFixed(2);
        const pastCgpa = parseFloat(document.getElementById('pastCgpa').value);
        const pastCredits = parseFloat(document.getElementById('pastCredits').value);

        // Calculate new CGPA
        const newTotalCredits = totalCredits + pastCredits;
        const newTotalGradePoints = (pastCgpa * pastCredits) + totalGradePoints;
        const newCGPA = (newTotalGradePoints / newTotalCredits).toFixed(2);

        // Update displayed values
        document.getElementById('totalHours').innerText = totalCredits;
        document.getElementById('currentGPA').innerText = currentGPA;
        document.getElementById('newCGPA').innerText = newCGPA;
    });
</script>

</body>
</html>
