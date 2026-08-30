<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REACH OUT Ministries - Sama-Bajau Students Initiative</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f6f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        
        /* Main Visual Cover Photo Banner Section */
        .cover-photo-banner {
            background: linear-gradient(rgba(4, 42, 32, 0.82), rgba(4, 42, 32, 0.82)), 
                        url('https://unsplash.com') no-repeat center center/cover;
            color: #f9fafb;
            text-align: center;
            padding: 90px 20px;
        }
        
        .cover-photo-banner h1 {
            font-size: 38px;
            margin: 0 0 10px 0;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .cover-photo-banner h2 {
            font-size: 28px;
            color: #fef08a; /* Golden Amber Highlight */
            margin: 0 0 15px 0;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-weight: 800;
        }

        .cover-photo-banner .tagline {
            font-size: 18px;
            font-style: italic;
            color: #ffffff;
            margin-bottom: 20px;
            font-weight: bold;
        }

        .container {
            max-width: 650px;
            margin: -30px auto 20px auto; /* Pull layout up slightly over cover banner edge */
            position: relative;
            background: #ffffff;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.15);
            z-index: 10;
        }

        h3 {
            color: #064e3b; /* Deep Ministry Green */
            text-align: center;
            margin-top: 5px;
            text-transform: uppercase;
            font-size: 18px;
            border-bottom: 2px solid #d97706;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .box {
            background: #fafafa;
            border: 1px solid #ddd;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 6px;
        }

        .bank-details {
            background-color: #ecfdf5;
            border: 2px dashed #064e3b;
            padding: 15px;
            border-radius: 6px;
        }

        .bank-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
            font-size: 15px;
        }

        .highlight {
            background: #fef08a;
            padding: 2px 5px;
            border-radius: 4px;
            font-weight: bold;
        }
        
        /* 30 Students Scrollable Container Box Layout */
        .students-scroll-box {
            max-height: 380px;
            overflow-y: scroll;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            padding: 10px;
            background: #ffffff;
            margin-top: 15px;
        }

        .student-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 1px solid #f1f5f9;
            padding: 12px 5px;
        }

        .student-row:last-child {
            border-bottom: none;
        }

        .student-title {
            font-weight: bold;
            color: #1e293b;
            font-size: 15px;
        }

        .student-meta {
            font-size: 12px;
            color: #64748b;
        }

        .btn-sponsor {
            background-color: #064e3b;
            color: white;
            border: none;
            padding: 6px 14px;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
            font-size: 13px;
            transition: all 0.2s;
        }

        .btn-sponsor:hover {
            background-color: #d97706;
        }

        .btn-sponsor.selected {
            background-color: #94a3b8;
            color: #ffffff;
            cursor: not-allowed;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 12px;
            color: #777;
        }
    </style>
</head>
<body>

    <!-- Cover Background Presentation Header -->
    <div class="cover-photo-banner">
        <h1>REACH OUT Ministries</h1>
        <h2>SAMA-BAJAU STUDENTS</h2>
        <div class="tagline">"The Heartbeat of Jesus Christ" — His command, Our Mission</div>
        <p style="max-width: 550px; margin: 0 auto; color: #e2e8f0; font-size: 15px;">Extending the unconditional love of Jesus for the LOST and UNREACHED PEOPLE GROUPS across Mindanao.</p>
    </div>

    <!-- Main Content Core Wrapper -->
    <div class="container">

        <!-- Missionary Profile Box -->
        <div class="box">
            <h3>Our Field Worker</h3>
            <p><strong>Worker Name:</strong> BJ BONGHAS BATE</p>
            <p><strong>Role:</strong> Missionary Pastor / Teacher (Mindanao Initiative Worker)</p>
            <p><strong>Assigned Area:</strong> Margosatubig, Zamboanga Del Sur</p>
            <p style="margin-bottom: 0;"><em>Pastor BJ serves unreached Muslim ethnic groups and Sama-Bajau coastal communities in Mindanao with local primary education, daily nutrition, literacy support, and gospel ministries.</em></p>
        </div>

        <!-- Child Sponsorship Section -->
        <div class="box">
            <h3>Student Sponsorship Program</h3>
            <p>Help an unreached child stay in classes with uniform clothes, notebook supplies, meal nutrition, and literacy materials. You can sponsor an individual slot locally or from abroad at any support level.</p>
            <p style="color: #d97706; font-weight: bold; text-align: center; margin-bottom: 5px;">Cost: ₱500 Pesos per month (Approx. $10 USD for foreigners)</p>
            
            <!-- Scrollable container generated cleanly via automation -->
            <div class="students-scroll-box" id="students-container">
                <!-- Javascript engine will automatically generate the 30 blank rows right here -->
            </div>
        </div>

        <!-- Bank Account / Remittance Section -->
        <div class="bank-details" id="donation-box">
            <h3 style="margin-top: 0; border-bottom: 1px solid #064e3b;">How to Send Support</h3>
            <p style="font-size: 14px; margin-bottom: 15px;">You can deposit local support offerings or international sponsorships of <strong>any amount</strong> directly into Pastor BJ's verified bank account parameters:</p>
            
            <div class="bank-row">
                <span><strong>Bank Name:</strong></span>
                <span>GoTyme Bank</span>
            </div>
            <div class="bank-row">
                <span><strong>Account Holder:</strong></span>
                <span>BJ BONGHAS BATE</span>
            </div>
            <div class="bank-row">
                <span><strong>Account Number:</strong></span>
                <span class="highlight">012922075777</span>
            </div>
            <div class="bank-row">
                <span><strong>SWIFT Code:</strong></span>
                <span>GOTYPHM2XXX</span>
            </div>
            <p style="font-size: 12px; color: #555; margin-top: 15px; text-align: center; line-height: 1.4;">
                <em>Foreign donors can transfer any USD amount quickly using digital remittance networks like <strong>Wise, Remitly, or WorldRemit</strong> targeted directly to the GoTyme bank details listed above.</em>
            </p>
        </div>

        <!-- Ministry Video/Photo Updates Placeholder -->
        <div class="box" style="margin-top: 20px; margin-bottom: 0;">
            <h3>Ministry Activity Updates</h3>
            <p style="text-align: center; color: #666; font-style: italic; margin-bottom: 0;">Ongoing outreach reports, study photos, and community distribution videos will be posted here regularly.</p>
        </div>

        <footer>
            <p>&copy; 2026 REACH OUT Ministries • Margosatubig Field Mission</p>
        </footer>
    </div>

    <!-- Script Processing Engine Layout Configuration -->
    <script>
        // Automatically build exactly 30 simple uniform slots on load
        const totalStudents = 30;
        const container = document.getElementById('students-container');
        
        let htmlContent = '';
        for (let i = 1; i <= totalStudents; i++) {
            htmlContent += `
                <div class="student-row">
                    <div>
                        <span class="student-title">Sama-Bajau Student Slot #${i}</span>
                        <div class="student-meta">Margosatubig Outreach Village • ₱500 / $10 USD month</div>
                    </div>
                    <button class="btn-sponsor" id="btn-${i}" onclick="selectStudent(${i})">Sponsor</button>
                </div>
            `;
        }
        container.innerHTML = htmlContent;

        // Interactive status handler mapping action variables
        function selectStudent(slotNumber) {
            const currentBtn = document.getElementById(`btn-${slotNumber}`);
            
            currentBtn.innerText = "Sponsorship Pending ✓";
            currentBtn.className = "btn-sponsor selected";
            currentBtn.disabled = true;

            alert(`Thank you for choosing to support Sama-Bajau Student Slot #${slotNumber}!\n\nPlease send your ₱500 PHP ($10 USD) monthly sponsorship commitment directly using the GoTyme Bank credentials displayed at the bottom of the layout.`);
            
            // Auto scroll down to focus view onto payment information

