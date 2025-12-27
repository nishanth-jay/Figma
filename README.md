# Ex08 Event Registration Web Application
# Date:14-12-2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

<style>
    .sports-day-container {
      background-color: rgba(184, 251, 254, 1);
      display: flex;
      max-width: 480px;
      width: 100%;
      flex-direction: column;
      overflow: hidden;
      align-items: center;
      text-align: center;
      margin: 0 auto;
      padding: 11px 0 29px;
      font: 400 36px Inter, sans-serif;
    }
    .header-banner {
      aspect-ratio: 5.05;
      object-fit: contain;
      object-position: center;
      width: 100%;
      align-self: stretch;
    }
    .sports-logo {
      aspect-ratio: 1.22;
      object-fit: contain;
      object-position: center;
      width: 174px;
      margin-top: 127px;
      max-width: 100%;
    }
    .event-title {
      color: rgba(10, 101, 36, 1);
      font-size: 32px;
      margin-top: 29px;
    }
    .action-button {
      width: 243px;
      max-width: 100%;
      white-space: nowrap;
      background-color: rgba(250, 19, 19, 1);
      color: rgba(24, 5, 5, 1);
    }
    .login-button {
      composes: action-button;
      margin-top: 69px;
      padding: 22px 66px 7px;
    }
    .register-button {
      composes: action-button;
      margin-top: 85px;
      padding: 24px 38px;
      background-color: rgba(252, 17, 17, 1);
      color: rgba(27, 10, 10, 1);
    }
    .tagline {
      color: rgba(0, 0, 0, 1);
      font-size: 24px;
      margin-top: 161px;
    }
    .visually-hidden {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      border: 0;
    }
  </style>
  
  <div class="sports-day-container">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/7b81d1b67bf37b0cb6f07763412255051530d8b37b61b00cc39256dd336ad822?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
      class="header-banner"
      alt="Sports Day Event Banner"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/49b959969752471b113e363e8fd54d0a769fa42cc4f17f091406f44efacf2284?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
      class="sports-logo"
      alt="Sports Event Logo"
    />
    <h1 class="event-title">SPORTS DAY EVENTS</h1>
    <button class="login-button" tabindex="0">LOGIN</button>
    <button class="register-button" tabindex="0">REGISTER</button>
    <p class="tagline">"BORN TO WIN"</p>
  </div>
  <style>
    .sports-events-container {
      background-color: #fff;
      display: flex;
      max-width: 480px;
      width: 100%;
      flex-direction: column;
      overflow: hidden;
      margin: 0 auto;
    }
    
    .sports-content {
      display: flex;
      flex-direction: column;
      position: relative;
      min-height: 956px;
      width: 100%;
      align-items: start;
      padding: 111px 35px 171px;
    }
    
    .background-image {
      position: absolute;
      inset: 0;
      height: 100%;
      width: 100%;
      object-fit: cover;
      object-position: center;
    }
    
    .main-title {
      position: relative;
      color: #08C249;
      text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
      text-align: center;
      margin-left: 19px;
      font: 400 32px Inter, sans-serif;
    }
    
    .sport-item {
      position: relative;
      display: flex;
      gap: 40px;
      color: #D81A1A;
      text-align: center;
      font: 400 28px Inter, sans-serif;
    }
    
    .sport-icon {
      aspect-ratio: 0.84;
      object-fit: contain;
      object-position: center;
      width: 38px;
    }
    
    .sport-name {
      margin-top: 16px;
    }
    
    .cricket-section { margin-top: 145px; }
    .football-section { margin-top: 43px; }
    .running-section { margin-top: 38px; }
    .volleyball-section { margin-top: 43px; }
    .hockey-section { 
      margin: 38px 0 -34px;
      color: #F41D3D;
    }
    
    .dual-sports {
      position: relative;
      display: flex;
      gap: 38px;
    }
    
    .dual-icons {
      align-self: start;
      display: flex;
      flex-direction: column;
    }
    
    .dual-names {
      display: flex;
      flex-direction: column;
      text-align: center;
      font: 400 28px Inter, sans-serif;
    }
    
    .volleyball-text {
      color: #FA1418;
    }
    
    .kabaddi-text {
      color: #D81A1A;
      align-self: start;
      margin-top: 36px;
    }
    
    .visually-hidden {
      position: absolute;
      width: 1px;
      height: 1px;
      padding: 0;
      margin: -1px;
      overflow: hidden;
      clip: rect(0, 0, 0, 0);
      border: 0;
    }
    </style>
    
    <div class="sports-events-container">
      <div class="sports-content">
        <img
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/3d1990b310493fe459cf8f20916942801302e0910e3c2985b9e930eb755d8e26?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
          alt=""
          class="background-image"
          loading="lazy"
        />
        <h1 class="main-title">SPORTS DAY EVENTS</h1>
        
        <div class="sport-item cricket-section">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/d258043574c8c8a028bdf90f2ba33ec0779a18a72ca71d9b6b353befd497f646?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
            alt="Cricket sport icon"
            class="sport-icon"
            loading="lazy"
          />
          <span class="sport-name">CRICKET</span>
        </div>
    
        <div class="sport-item football-section">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/4c7b994a05612a1bab471bde64ba16aca2cc1699522e7e75dc1b2f1105e574f5?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
            alt="Football sport icon"
            class="sport-icon"
            loading="lazy"
          />
          <span class="sport-name">FOOTBALL</span>
        </div>
    
        <div class="sport-item running-section">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/90e6668c9773718f5844ed1b82d6f1edb162e1ce02784356ad9677644f2681f0?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
            alt="Running sport icon"
            class="sport-icon"
            loading="lazy"
          />
          <span class="sport-name">RUNNING</span>
        </div>
    
        <div class="dual-sports volleyball-section">
          <div class="dual-icons">
            <img
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/478b51987d63f0c0688e61e8e387ae027170a101a125c2545f5e0bb381083187?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
              alt="Volleyball sport icon"
              class="sport-icon"
              loading="lazy"
            />
            <img
              src="https://cdn.builder.io/api/v1/image/assets/TEMP/16f764b25909282d5afcf46fcfeb7ada93083fd9fe62ad26cbce5e70a7c7ff40?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
              alt="Kabaddi sport icon"
              class="sport-icon"
              loading="lazy"
            />
          </div>
          <div class="dual-names">
            <span class="volleyball-text">VOLLEY BALL<br /></span>
            <span class="kabaddi-text">KABADDI</span>
          </div>
        </div>
    
        <div class="sport-item hockey-section">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/2586a84ab5c54b314edd6ded213c6db8bd4b66ee0e1f04cc982e399509b4972f?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
            alt="Hockey sport icon"
            class="sport-icon"
            loading="lazy"
          />
          <span class="sport-name">HOCKEY</span>
        </div>
      </div>
    </div>
    <style>
        .registration-container {
          background-color: rgba(249, 143, 255, 1);
          display: flex;
          max-width: 480px;
          width: 100%;
          flex-direction: column;
          overflow: hidden;
          margin: 0 auto;
          padding: 13px 0 66px;
        }
        
        .header-logo {
          aspect-ratio: 5.05;
          object-fit: contain;
          object-position: center;
          width: 100%;
        }
        
        .form-wrapper {
          display: flex;
          margin-top: 55px;
          width: 100%;
          flex-direction: column;
          align-items: start;
          padding: 0 34px 0 14px;
        }
        
        .form-title {
          font: 400 36px Inter, sans-serif;
          margin-left: 19px;
          color: rgba(0, 0, 0, 1);
        }
        
        .form-field {
          background-color: rgba(217, 217, 217, 1);
          width: 380px;
          max-width: 100%;
          padding: 18px;
          margin-top: 25px;
          font: 400 16px Inter, sans-serif;
        }
        
        .form-field-spacing {
          margin-top: 39px;
        }
        
        .submit-button {
          background-color: rgba(217, 217, 217, 1);
          align-self: center;
          margin-top: 45px;
          width: 250px;
          max-width: 100%;
          font-size: 26px;
          padding: 19px 59px;
          border: none;
          cursor: pointer;
        }
        
        .visually-hidden {
          position: absolute;
          width: 1px;
          height: 1px;
          padding: 0;
          margin: -1px;
          overflow: hidden;
          clip: rect(0, 0, 0, 0);
          border: 0;
        }
        </style>
        
        <div class="registration-container">
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/7b81d1b67bf37b0cb6f07763412255051530d8b37b61b00cc39256dd336ad822?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
            alt="Registration form header"
            class="header-logo"
          />
          
          <form class="form-wrapper">
            <h1 class="form-title">REGISTRATION FORM</h1>
            
            <label for="fullName" class="visually-hidden">Full Name</label>
            <input type="text" id="fullName" class="form-field" placeholder="FULL NAME" required aria-label="Full Name"/>
            
            <label for="age" class="visually-hidden">Age</label>
            <input type="number" id="age" class="form-field form-field-spacing" placeholder="AGE" required aria-label="Age"/>
            
            <label for="email" class="visually-hidden">Email ID</label>
            <input type="email" id="email" class="form-field form-field-spacing" placeholder="EMAIL ID" required aria-label="Email ID"/>
            
            <label for="mobile" class="visually-hidden">Mobile Number</label>
            <input type="tel" id="mobile" class="form-field" placeholder="MOBILE NUMBER" required aria-label="Mobile Number"/>
            
            <label for="gender" class="visually-hidden">Gender</label>
            <select id="gender" class="form-field form-field-spacing" required aria-label="Gender">
              <option value="" disabled selected>GENDER</option>
              <option value="male">Male</option>
              <option value="female">Female</option>
              <option value="other">Other</option>
            </select>
            
            <label for="events" class="visually-hidden">Events to Register</label>
            <select id="events" class="form-field form-field-spacing" required aria-label="Events to Register">
              <option value="" disabled selected>EVENTS TO REGISTER</option>
              <option value="event1">Event 1</option>
              <option value="event2">Event 2</option>
              <option value="event3">Event 3</option>
            </select>
            
            <button type="submit" class="submit-button">REGISTER</button>
          </form>
        </div>
        <style>
            .thank-you-container {
              background: #fff;
              display: flex;
              max-width: 480px;
              width: 100%;
              flex-direction: column;
              overflow: hidden;
              align-items: center;
              font-family: Inter, sans-serif;
              color: #000;
              font-weight: 700;
              text-align: center;
              margin: 0 auto;
              padding: 23px 0 71px;
            }
            
            .header-logo {
              aspect-ratio: 4.95;
              object-fit: contain;
              object-position: center;
              width: 100%;
              align-self: stretch;
            }
            
            .main-title {
              font-size: 48px;
              margin-top: 193px;
            }
            
            .event-description {
              font-size: 24px;
              margin-top: 63px;
            }
            
            .contact-heading {
              font-size: 32px;
              margin-top: 177px;
            }
            
            .contact-email {
              font-size: 28px;
              margin-top: 63px;
            }
            
            .contact-phone {
              font-size: 28px;
              margin-top: 36px;
            }
            
            .visually-hidden {
              position: absolute;
              width: 1px;
              height: 1px;
              padding: 0;
              margin: -1px;
              overflow: hidden;
              clip: rect(0, 0, 0, 0);
              border: 0;
            }
            </style>
            
            <div class="thank-you-container">
              <img
                loading="lazy"
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/8220df2e653c392a90ba8d57332f2aa7f3db4641cc27fe51dd8ff5535833ce1a?placeholderIfAbsent=true&apiKey=901bc1bb6f5543d19f0498bfa11f96f1"
                class="header-logo"
                alt="Sports Day Event Logo"
              />
              <h1 class="main-title">THANK YOU</h1>
              <p class="event-description">
                WE ARE ALL WAITING FOR
                <br />
                ALL YOUR PARTICIPATION IN
                <br />
                SPORTS DAY EVENT
              </p>
              <h2 class="contact-heading">CONTACT US</h2>
              <p class="contact-email">EMAIL: sec@gmail.com</p>
              <p class="contact-phone">PHONE:1234567890</p>
            </div>
</body>
</html>
```
# OUTPUT:
<img width="1337" height="858" alt="397298306-f67064a6-917a-4835-a217-6380c649ccec" src="https://github.com/user-attachments/assets/46cdf299-880d-4e0f-b5b1-027d153b7222" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
