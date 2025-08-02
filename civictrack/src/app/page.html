<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CivicTrack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
        }

        .app-container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            min-height: 100vh;
            box-shadow: 0 0 30px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
        }

        .screen {
            display: none;
            padding: 20px;
            min-height: 100vh;
            position: relative;
        }

        .screen.active {
            display: block;
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            padding-bottom: 15px;
            border-bottom: 2px solid #f0f0f0;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #667eea;
        }

        .header-buttons {
            display: flex;
            gap: 10px;
        }

        .login-btn, .home-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 20px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.3s ease;
        }

        .login-btn:hover, .home-btn:hover {
            background: #5a6fd8;
            transform: translateY(-2px);
        }

        .search-container {
            position: relative;
            margin-bottom: 20px;
        }

        .search-input {
            width: 100%;
            padding: 12px 40px 12px 16px;
            border: 2px solid #e0e0e0;
            border-radius: 25px;
            font-size: 16px;
            outline: none;
            transition: border-color 0.3s ease;
        }

        .search-input:focus {
            border-color: #667eea;
        }

        .search-btn {
            position: absolute;
            right: 5px;
            top: 50%;
            transform: translateY(-50%);
            background: #667eea;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 20px;
            cursor: pointer;
        }

        .filters {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            flex-wrap: wrap;
        }

        .filter-btn {
            padding: 8px 16px;
            border: 2px solid #e0e0e0;
            background: white;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .filter-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }

        .issues-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .issue-card {
            border: 2px solid #e0e0e0;
            border-radius: 15px;
            overflow: hidden;
            transition: all 0.3s ease;
            cursor: pointer;
            background: white;
        }

        .issue-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-color: #667eea;
        }

        .issue-image {
            width: 100%;
            height: 150px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 18px;
            font-weight: bold;
        }

        .issue-content {
            padding: 15px;
        }

        .issue-title {
            font-weight: bold;
            margin-bottom: 5px;
            color: #333;
        }

        .issue-description {
            font-size: 14px;
            color: #666;
            margin-bottom: 10px;
        }

        .issue-meta {
            font-size: 12px;
            color: #999;
        }

        .pagination {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }

        .page-btn {
            width: 30px;
            height: 30px;
            border: 1px solid #ddd;
            background: white;
            border-radius: 50%;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .page-btn.active {
            background: #667eea;
            color: white;
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            border-radius: 20px;
            background: white;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
            color: #333;
        }

        .form-input {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            font-size: 16px;
            outline: none;
            transition: border-color 0.3s ease;
        }

        .form-input:focus {
            border-color: #667eea;
        }

        .form-btn {
            width: 100%;
            padding: 12px;
            background: #667eea;
            color: white;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .form-btn:hover {
            background: #5a6fd8;
        }

        .form-link {
            text-align: center;
            margin-top: 15px;
        }

        .form-link a {
            color: #667eea;
            text-decoration: none;
        }

        .issue-detail {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            margin-bottom: 20px;
        }

        .issue-detail-image {
            width: 100%;
            height: 200px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 24px;
            font-weight: bold;
        }

        .issue-detail-content {
            padding: 20px;
        }

        .status-badge {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 12px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .status-reported {
            background: #ffeaa7;
            color: #d63031;
        }

        .activity-section {
            background: #f8f9fa;
            border-radius: 10px;
            padding: 15px;
            margin-top: 15px;
        }

        .mobile-nav {
            position: fixed;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            max-width: 800px;
            width: 100%;
            background: white;
            border-top: 1px solid #e0e0e0;
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
        }

        .nav-btn {
            background: none;
            border: none;
            padding: 10px;
            cursor: pointer;
            color: #666;
            font-size: 12px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 5px;
        }

        .nav-btn.active {
            color: #667eea;
        }

        .report-form {
            background: white;
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 80px;
        }

        .map-placeholder {
            width: 100%;
            height: 200px;
            background: #f0f0f0;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #666;
            margin-bottom: 15px;
        }

        @media (max-width: 768px) {
            .app-container {
                max-width: 100%;
            }
            
            .issues-grid {
                grid-template-columns: 1fr;
            }
            
            .filters {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="app-container">
        <!-- Home Screen -->
        <div id="home" class="screen active">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <div class="header-buttons">
                    <button class="login-btn" onclick="showScreen('register')">Register</button>
                    <button class="login-btn" onclick="showScreen('login')">Login</button>
                </div>
            </div>
            
            <p style="text-align: center; color: #666; margin-bottom: 20px;">
                User can also able to see nearby issues without Login
            </p>
            
            <div class="search-container">
                <input type="text" class="search-input" placeholder="Search issues...">
                <button class="search-btn">🔍</button>
            </div>
            
            <div class="filters">
                <button class="filter-btn active">Categories</button>
                <button class="filter-btn">Status</button>
                <button class="filter-btn">Distance</button>
            </div>
            
            <div class="issues-grid">
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🚧</div>
                    <div class="issue-content">
                        <div class="issue-title">Streetlight not working</div>
                        <div class="issue-description">Street light not working from last 4 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🕳️</div>
                    <div class="issue-content">
                        <div class="issue-title">Pothole on main road</div>
                        <div class="issue-description">Large pothole causing traffic issues</div>
                        <div class="issue-meta">📍 Local neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🗑️</div>
                    <div class="issue-content">
                        <div class="issue-title">Garbage not collected</div>
                        <div class="issue-description">Waste collection missed for 3 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🚧</div>
                    <div class="issue-content">
                        <div class="issue-title">Streetlight not working</div>
                        <div class="issue-description">Street light not working from last 4 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🕳️</div>
                    <div class="issue-content">
                        <div class="issue-title">Pothole on main road</div>
                        <div class="issue-description">Large pothole causing traffic issues</div>
                        <div class="issue-meta">📍 Local neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🗑️</div>
                    <div class="issue-content">
                        <div class="issue-title">Garbage not collected</div>
                        <div class="issue-description">Waste collection missed for 3 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
            </div>
            
            <div class="pagination">
                <button class="page-btn active">1</button>
                <button class="page-btn">2</button>
                <button class="page-btn">3</button>
                <button class="page-btn">4</button>
                <button class="page-btn">11</button>
                <button class="page-btn">></button>
            </div>
        </div>

        <!-- Login Screen -->
        <div id="login" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('home')">Home</button>
            </div>
            
            <div class="form-container">
                <h2 style="text-align: center; margin-bottom: 30px; color: #333;">User Login</h2>
                
                <div class="form-group">
                    <label class="form-label">User Name</label>
                    <input type="text" class="form-input" placeholder="Enter username">
                </div>
                
                <div class="form-group">
                    <label class="form-label">Password</label>
                    <input type="password" class="form-input" placeholder="Enter password">
                </div>
                
                <button class="form-btn" onclick="handleLogin()">Login</button>
                
                <div class="form-link">
                    Don't have an account? <a href="#" onclick="showScreen('register')">Register here</a>
                </div>
            </div>
        </div>

        <!-- Registration Screen -->
        <div id="register" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('home')">Home</button>
            </div>
            
            <div class="form-container">
                <h2 style="text-align: center; margin-bottom: 30px; color: #333;">Create Account</h2>
                
                <div class="form-group">
                    <label class="form-label">Full Name</label>
                    <input type="text" class="form-input" placeholder="Enter your full name" required>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Email Address</label>
                    <input type="email" class="form-input" placeholder="Enter your email" required>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Phone Number</label>
                    <input type="tel" class="form-input" placeholder="Enter your phone number" required>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Create Password</label>
                    <input type="password" class="form-input" placeholder="Create a strong password" required>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Confirm Password</label>
                    <input type="password" class="form-input" placeholder="Confirm your password" required>
                </div>
                
                <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 20px;">
                    <input type="checkbox" id="terms" required>
                    <label for="terms" style="font-size: 14px; color: #666;">
                        I agree to the <a href="#" style="color: #667eea;">Terms of Service</a> and <a href="#" style="color: #667eea;">Privacy Policy</a>
                    </label>
                </div>
                
                <button class="form-btn" onclick="handleRegister()">Create Account</button>
                
                <div class="form-link">
                    Already have an account? <a href="#" onclick="showScreen('login')">Sign in here</a>
                </div>
            </div>
        </div>

        <!-- User Home Screen (After Login) -->
        <div id="userHome" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="logout()">Logout</button>
            </div>
            
            <div class="search-container">
                <input type="text" class="search-input" placeholder="Search issues...">
                <button class="search-btn">🔍</button>
            </div>
            
            <div class="filters">
                <button class="filter-btn active">Categories</button>
                <button class="filter-btn">Status</button>
                <button class="filter-btn">Distance</button>
            </div>
            
            <div class="issues-grid">
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🚧</div>
                    <div class="issue-content">
                        <div class="issue-title">Streetlight not working</div>
                        <div class="issue-description">Street light not working from last 4 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🕳️</div>
                    <div class="issue-content">
                        <div class="issue-title">Pothole on main road</div>
                        <div class="issue-description">Large pothole causing traffic issues</div>
                        <div class="issue-meta">📍 Local neighborhood</div>
                    </div>
                </div>
                
                <div class="issue-card" onclick="showScreen('issueDetail')">
                    <div class="issue-image">🗑️</div>
                    <div class="issue-content">
                        <div class="issue-title">Garbage not collected</div>
                        <div class="issue-description">Waste collection missed for 3 days</div>
                        <div class="issue-meta">📍 Nearby neighborhood</div>
                    </div>
                </div>
            </div>
            
            <div class="pagination">
                <button class="page-btn active">1</button>
                <button class="page-btn">2</button>
                <button class="page-btn">3</button>
                <button class="page-btn">4</button>
                <button class="page-btn">11</button>
                <button class="page-btn">></button>
            </div>
        </div>

        <!-- Issue Detail Screen -->
        <div id="issueDetail" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('userHome')">Back</button>
            </div>
            
            <div class="issue-detail">
                <div class="issue-detail-image">🕳️</div>
                <div class="issue-detail-content">
                    <div class="status-badge status-reported">Reported by Anonymous</div>
                    <h2>Pothole on C.G road pheezabadi, is riddled with potholes, making it dangerous and difficult to travel on.</h2>
                    <p style="color: #666; margin: 15px 0;">Location: C.G road pheezabadi opposite begonia</p>
                    
                    <div class="activity-section">
                        <h3 style="margin-bottom: 10px;">Activity</h3>
                        <div style="font-size: 14px; color: #666;">
                            <div>Jun 02, 2025 - 10:34 AM - Reported by user</div>
                            <div>Jul 26, 2025 - Assigned to municipal worker</div>
                            <div>Jul 28, 2025 - Contact In Progress</div>
                        </div>
                    </div>
                    
                    <div class="map-placeholder" style="margin-top: 15px;">
                        🗺️ Map Location
                    </div>
                </div>
            </div>
        </div>

        <!-- Report Issue Screen -->
        <div id="reportIssue" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('userHome')">Back</button>
            </div>
            
            <div class="report-form">
                <p style="text-align: center; margin-bottom: 20px; color: #666;">
                    Should also compatible with mobile
                </p>
                
                <div class="search-container">
                    <input type="text" class="search-input" placeholder="Search Issues">
                    <button class="search-btn">🔍</button>
                </div>
                
                <div class="issues-grid" style="margin-bottom: 20px;">
                    <div class="issue-card">
                        <div class="issue-image">🚧</div>
                        <div class="issue-content">
                            <div class="issue-title">Streetlight not working</div>
                            <div class="issue-description">Street light not working from last 4 days</div>
                            <div class="issue-meta">📍 Nearby neighborhood</div>
                        </div>
                    </div>
                    
                    <div class="issue-card">
                        <div class="issue-image">🕳️</div>
                        <div class="issue-content">
                            <div class="issue-title">Pothole on main road</div>
                            <div class="issue-description">Large pothole causing traffic issues</div>
                            <div class="issue-meta">📍 Local neighborhood</div>
                        </div>
                    </div>
                    
                    <div class="issue-card">
                        <div class="issue-image">🗑️</div>
                        <div class="issue-content">
                            <div class="issue-title">Garbage not collected</div>
                            <div class="issue-description">Waste collection missed for 3 days</div>
                            <div class="issue-meta">📍 Nearby neighborhood</div>
                        </div>
                    </div>
                </div>
                
                <button class="form-btn" onclick="showScreen('reportForm')">Report New Issue</button>
            </div>
        </div>

        <!-- Profile Screen -->
        <div id="profile" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('userHome')">Back</button>
            </div>
            
            <div class="form-container" style="max-width: 500px;">
                <div style="text-align: center; margin-bottom: 30px;">
                    <div style="width: 80px; height: 80px; background: linear-gradient(135deg, #667eea, #764ba2); border-radius: 50%; margin: 0 auto 15px; display: flex; align-items: center; justify-content: center; color: white; font-size: 32px; font-weight: bold;">
                        👤
                    </div>
                    <h2 style="color: #333; margin-bottom: 5px;">User Profile</h2>
                    <p style="color: #666; font-size: 14px;">Manage your account information</p>
                </div>
                
                <div class="profile-section" style="margin-bottom: 30px;">
                    <h3 style="color: #333; margin-bottom: 15px; border-bottom: 2px solid #f0f0f0; padding-bottom: 10px;">Personal Information</h3>
                    
                    <div class="form-group">
                        <label class="form-label">Full Name</label>
                        <input type="text" class="form-input" id="profileName" value="John Doe">
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label">Email Address</label>
                        <input type="email" class="form-input" id="profileEmail" value="john.doe@example.com">
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label">Phone Number</label>
                        <input type="tel" class="form-input" id="profilePhone" value="+1 (555) 123-4567">
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label">Address</label>
                        <textarea class="form-input" rows="3" id="profileAddress" placeholder="Enter your address for better location services">123 Main Street, Panchkula, Haryana, India</textarea>
                    </div>
                </div>
                
                <div class="profile-section" style="margin-bottom: 30px;">
                    <h3 style="color: #333; margin-bottom: 15px; border-bottom: 2px solid #f0f0f0; padding-bottom: 10px;">Activity Summary</h3>
                    
                    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 15px; margin-bottom: 20px;">
                        <div style="text-align: center; padding: 15px; background: #f8f9fa; border-radius: 10px;">
                            <div style="font-size: 24px; font-weight: bold; color: #667eea;">7</div>
                            <div style="font-size: 12px; color: #666;">Issues Reported</div>
                        </div>
                        <div style="text-align: center; padding: 15px; background: #f8f9fa; border-radius: 10px;">
                            <div style="font-size: 24px; font-weight: bold; color: #28a745;">4</div>
                            <div style="font-size: 12px; color: #666;">Issues Resolved</div>
                        </div>
                        <div style="text-align: center; padding: 15px; background: #f8f9fa; border-radius: 10px;">
                            <div style="font-size: 24px; font-weight: bold; color: #ffc107;">3</div>
                            <div style="font-size: 12px; color: #666;">In Progress</div>
                        </div>
                    </div>
                </div>
                
                <div class="profile-section" style="margin-bottom: 30px;">
                    <h3 style="color: #333; margin-bottom: 15px; border-bottom: 2px solid #f0f0f0; padding-bottom: 10px;">My Recent Issues</h3>
                    
                    <div style="space-y: 10px;">
                        <div style="padding: 12px; border: 1px solid #e0e0e0; border-radius: 8px; margin-bottom: 10px;">
                            <div style="display: flex; justify-content: between; align-items: start;">
                                <div style="flex: 1;">
                                    <div style="font-weight: 500; color: #333; margin-bottom: 4px;">Streetlight not working</div>
                                    <div style="font-size: 12px; color: #666;">Reported on Jun 15, 2025</div>
                                </div>
                                <span style="background: #28a745; color: white; padding: 2px 8px; border-radius: 12px; font-size: 10px;">Resolved</span>
                            </div>
                        </div>
                        
                        <div style="padding: 12px; border: 1px solid #e0e0e0; border-radius: 8px; margin-bottom: 10px;">
                            <div style="display: flex; justify-content: between; align-items: start;">
                                <div style="flex: 1;">
                                    <div style="font-weight: 500; color: #333; margin-bottom: 4px;">Pothole on main road</div>
                                    <div style="font-size: 12px; color: #666;">Reported on Jul 02, 2025</div>
                                </div>
                                <span style="background: #ffc107; color: white; padding: 2px 8px; border-radius: 12px; font-size: 10px;">In Progress</span>
                            </div>
                        </div>
                        
                        <div style="padding: 12px; border: 1px solid #e0e0e0; border-radius: 8px; margin-bottom: 10px;">
                            <div style="display: flex; justify-content: between; align-items: start;">
                                <div style="flex: 1;">
                                    <div style="font-weight: 500; color: #333; margin-bottom: 4px;">Garbage not collected</div>
                                    <div style="font-size: 12px; color: #666;">Reported on Jul 28, 2025</div>
                                </div>
                                <span style="background: #dc3545; color: white; padding: 2px 8px; border-radius: 12px; font-size: 10px;">Pending</span>
                            </div>
                        </div>
                    </div>
                    
                    <button style="width: 100%; padding: 8px; background: none; border: 2px dashed #667eea; color: #667eea; border-radius: 8px; cursor: pointer; margin-top: 10px;" onclick="showScreen('userHome')">
                        View All My Issues
                    </button>
                </div>
                
                <div class="profile-section" style="margin-bottom: 30px;">
                    <h3 style="color: #333; margin-bottom: 15px; border-bottom: 2px solid #f0f0f0; padding-bottom: 10px;">Preferences</h3>
                    
                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 10px 0; border-bottom: 1px solid #f0f0f0;">
                        <span style="color: #333;">Email Notifications</span>
                        <label style="position: relative; display: inline-block; width: 50px; height: 24px;">
                            <input type="checkbox" checked style="opacity: 0; width: 0; height: 0;">
                            <span style="position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #667eea; transition: .4s; border-radius: 24px; &:before { position: absolute; content: ''; height: 18px; width: 18px; left: 3px; bottom: 3px; background-color: white; transition: .4s; border-radius: 50%; }"></span>
                        </label>
                    </div>
                    
                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 10px 0; border-bottom: 1px solid #f0f0f0;">
                        <span style="color: #333;">SMS Notifications</span>
                        <label style="position: relative; display: inline-block; width: 50px; height: 24px;">
                            <input type="checkbox" style="opacity: 0; width: 0; height: 0;">
                            <span style="position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #ccc; transition: .4s; border-radius: 24px;"></span>
                        </label>
                    </div>
                    
                    <div style="display: flex; justify-content: space-between; align-items: center; padding: 10px 0;">
                        <span style="color: #333;">Location Services</span>
                        <label style="position: relative; display: inline-block; width: 50px; height: 24px;">
                            <input type="checkbox" checked style="opacity: 0; width: 0; height: 0;">
                            <span style="position: absolute; cursor: pointer; top: 0; left: 0; right: 0; bottom: 0; background-color: #667eea; transition: .4s; border-radius: 24px;"></span>
                        </label>
                    </div>
                </div>
                
                <div style="display: flex; gap: 10px; margin-bottom: 20px;">
                    <button class="form-btn" onclick="updateProfile()" style="background: #28a745;">Save Changes</button>
                    <button class="form-btn" onclick="showChangePasswordModal()" style="background: #6c757d;">Change Password</button>
                </div>
                
                <div style="text-align: center; padding-top: 20px; border-top: 1px solid #f0f0f0;">
                    <button onclick="logout()" style="background: none; border: none; color: #dc3545; cursor: pointer; text-decoration: underline;">
                        Sign Out
                    </button>
                </div>
            </div>
        </div>
        <div id="reportForm" class="screen">
            <div class="header">
                <div class="logo">CivicTrack</div>
                <button class="home-btn" onclick="showScreen('reportIssue')">Back</button>
            </div>
            
            <div class="report-form">
                <h2 style="text-align: center; margin-bottom: 20px;">Report New Issue</h2>
                
                <p style="text-align: center; margin-bottom: 20px; color: #666;">
                    User can edit location profile for quick doing it from top bar
                </p>
                
                <div class="map-placeholder">
                    📍 Select Location on Map
                </div>
                
                <div class="form-group">
                    <label class="form-label">Category</label>
                    <select class="form-input">
                        <option>Road Issues</option>
                        <option>Street Lighting</option>
                        <option>Waste Management</option>
                        <option>Water Supply</option>
                        <option>Other</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Description</label>
                    <textarea class="form-input" rows="4" placeholder="Describe the issue in detail..."></textarea>
                </div>
                
                <div class="form-group">
                    <label class="form-label">Upload Photos</label>
                    <input type="file" class="form-input" multiple accept="image/*">
                </div>
                
                <div style="display: flex; gap: 10px;">
                    <button class="form-btn" style="background: #28a745;" onclick="alert('Issue reported successfully!')">Submit Issue</button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation -->
        <div class="mobile-nav" style="display: none;">
            <button class="nav-btn active" onclick="showScreen('userHome')">
                <span>🏠</span>
                <span>Home</span>
            </button>
            <button class="nav-btn" onclick="showScreen('reportIssue')">
                <span>📝</span>
                <span>Report</span>
            </button>
            <button class="nav-btn" onclick="showScreen('profile')">
                <span>👤</span>
                <span>Profile</span>
            </button>
        </div>
    </div>

    <script>
        // Authentication state
        let isLoggedIn = false;
        let currentUser = null;

        function login(username) {
            isLoggedIn = true;
            currentUser = username;
            updateUIForLoggedInUser();
        }

        function logout() {
            isLoggedIn = false;
            currentUser = null;
            updateUIForLoggedOutUser();
            showScreen('home');
        }

        function updateUIForLoggedInUser() {
            // Show mobile navigation
            document.querySelector('.mobile-nav').style.display = 'flex';
        }

        function updateUIForLoggedOutUser() {
            // Hide mobile navigation
            document.querySelector('.mobile-nav').style.display = 'none';
        }

        function requireLogin(targetScreen) {
            if (!isLoggedIn) {
                alert('Please login first to access this feature');
                showScreen('login');
                return false;
            }
            return true;
        }

        function showScreen(screenId) {
            // Check if user needs to be logged in for certain screens
            const protectedScreens = ['userHome', 'reportIssue', 'reportForm', 'issueDetail', 'profile'];
            
            if (protectedScreens.includes(screenId) && !requireLogin(screenId)) {
                return;
            }

            // Hide all screens
            const screens = document.querySelectorAll('.screen');
            screens.forEach(screen => screen.classList.remove('active'));
            
            // Show selected screen
            document.getElementById(screenId).classList.add('active');
            
            // Update navigation active state only if logged in
            if (isLoggedIn) {
                const navBtns = document.querySelectorAll('.nav-btn');
                navBtns.forEach(btn => btn.classList.remove('active'));
                
                // Highlight appropriate nav button
                if (screenId === 'userHome') {
                    document.querySelector('.nav-btn').classList.add('active');
                } else if (screenId === 'reportIssue' || screenId === 'reportForm') {
                    document.querySelectorAll('.nav-btn')[1].classList.add('active');
                } else if (screenId === 'profile') {
                    document.querySelectorAll('.nav-btn')[2].classList.add('active');
                }
            }
            
            // Scroll to top
            window.scrollTo(0, 0);
        }

        // Handle login form submission
        function handleLogin() {
            const username = document.querySelector('#login .form-input[type="text"]').value;
            const password = document.querySelector('#login .form-input[type="password"]').value;
            
            if (username && password) {
                login(username);
                showScreen('userHome');
            } else {
                alert('Please enter both username and password');
            }
        }

        // Handle registration
        function handleRegister() {
            const fullName = document.querySelector('#register .form-input[type="text"]').value;
            const email = document.querySelector('#register .form-input[type="email"]').value;
            const phone = document.querySelector('#register .form-input[type="tel"]').value;
            const password = document.querySelectorAll('#register .form-input[type="password"]')[0].value;
            const confirmPassword = document.querySelectorAll('#register .form-input[type="password"]')[1].value;
            const termsAccepted = document.querySelector('#terms').checked;
            
            if (!fullName || !email || !phone || !password || !confirmPassword) {
                alert('Please fill in all fields');
                return;
            }
            
            if (password !== confirmPassword) {
                alert('Passwords do not match');
                return;
            }
            
            if (!termsAccepted) {
                alert('Please accept the Terms of Service and Privacy Policy');
                return;
            }
            
            alert('Registration successful! Please login with your credentials.');
            showScreen('login');
        }

        // Profile management functions
        function updateProfile() {
            const name = document.getElementById('profileName').value;
            const email = document.getElementById('profileEmail').value;
            const phone = document.getElementById('profilePhone').value;
            const address = document.getElementById('profileAddress').value;
            
            if (!name || !email || !phone) {
                alert('Please fill in all required fields');
                return;
            }
            
            // Here you would typically send data to server
            alert('Profile updated successfully!');
        }

        function showChangePasswordModal() {
            const newPassword = prompt('Enter new password:');
            const confirmPassword = prompt('Confirm new password:');
            
            if (newPassword && confirmPassword) {
                if (newPassword === confirmPassword) {
                    alert('Password changed successfully!');
                } else {
                    alert('Passwords do not match!');
                }
            }
        }

        // Filter button functionality
        document.addEventListener('click', function(e) {
            if (e.target.classList.contains('filter-btn')) {
                document.querySelectorAll('.filter-btn').forEach(btn => btn.classList.remove('active'));
                e.target.classList.add('active');
            }
            
            if (e.target.classList.contains('page-btn')) {
                document.querySelectorAll('.page-btn').forEach(btn => btn.classList.remove('active'));
                e.target.classList.add('active');
            }
        });

        // Add some interactive hover effects
        document.querySelectorAll('.issue-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-5px)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0)';
            });
        });

        // Initialize app
        document.addEventListener('DOMContentLoaded', function() {
            showScreen('home');
            updateUIForLoggedOutUser(); // Start with logged out state
        });
    </script>
</body>
</html>