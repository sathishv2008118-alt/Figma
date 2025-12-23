# Ex09 Event Registration Web Application
# Date:19\12\2025
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
```import { MobilePhone } from "./components/MobilePhone";
import { PhoneScreen1 } from "./components/PhoneScreen1";
import { PhoneScreen2 } from "./components/PhoneScreen2";
import { PhoneScreen3 } from "./components/PhoneScreen3";

export default function App() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-gray-100 to-gray-200 flex items-center justify-center p-8">
      <div className="flex flex-wrap items-center justify-center gap-8 max-w-7xl">
        <MobilePhone>
          <PhoneScreen1 />
        </MobilePhone>
        
        <MobilePhone>
          <PhoneScreen2 />
        </MobilePhone>
        
        <MobilePhone>
          <PhoneScreen3 />
        </MobilePhone>
      </div>
    </div>
  );
}
```
# OUTPUT:![alt text](<Screenshot 2025-12-23 205456.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
