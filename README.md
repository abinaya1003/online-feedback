![feedback](https://github.com/user-attachments/assets/daa0c804-7071-45de-b39a-df553ff2c489)
# online-feedback
submit feedback through an online form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Online Feedback System</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background: linear-gradient(to right, #74ebd5, #9face6);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .feedback-container {
            background-color: #ffffff;
            width: 380px;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.2);
        }

        h2 {
            text-align: center;
            color: #333;
            margin-bottom: 5px;
        }

        p {
            text-align: center;
            font-size: 14px;
            color: #666;
        }

        label {
            font-weight: bold;
            margin-top: 12px;
            display: block;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        textarea {
            resize: none;
        }

        button {
            width: 100%;
            margin-top: 15px;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }

        .footer-text {
            text-align: center;
            margin-top: 12px;
            font-size: 12px;
            color: gray;
        }
    </style>
</head>

<body>

<div class="feedback-container">
    <h2>Online Feedback System</h2>
    <p>Please share your valuable feedback</p>

    <form>
        <label>Full Name</label>
        <input type="text" placeholder="Enter your name" required>

        <label>Email Address</label>
        <input type="email" placeholder="Enter your email" required>

        <label>Rating</label>
        <select required>
            <option value="">Select Rating</option>
            <option>Excellent</option>
            <option>Very Good</option>
            <option>Good</option>
            <option>Average</option>
            <option>Poor</option>
        </select>

        <label>Your Feedback</label>
        <textarea rows="4" placeholder="Write your feedback here..." required></textarea>

        <button type="submit">Submit Feedback</button>
    </form>

    <p class="footer-text">© 2026 Online Feedback System</p>
</div>

</body>
</html>


