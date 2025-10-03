# Issue Templates Guide for Teachers

## Overview

We've created **5 easy-to-use issue templates** to help you request changes to the Mergington High School Activity Management System without needing to write code or understand technical details.

## What Are Issue Templates?

Issue templates are pre-formatted forms that guide you through providing all the necessary information for common tasks. They ensure that developers (or GitHub Copilot) have everything needed to complete your request quickly and accurately.

## Available Templates

### 1. 📝 Add New Extracurricular Activity

**When to use:** You want to add a brand new activity to the system.

**What you'll provide:**
- Activity name (e.g., "Photography Club")
- Description of the activity
- Activity type/category (Academic, Arts, Sports, Technology, etc.)
- Meeting days (checkboxes for each day of the week)
- Start and end times (in 24-hour format)
- Maximum number of participants
- Optional: Initial list of registered students

**Example use case:**
> "I want to add a new Robotics Club that meets on Wednesdays from 3:30 PM to 5:00 PM with a maximum of 20 students."

---

### 2. ✏️ Modify Existing Activity

**When to use:** You need to change something about an activity that's already in the system.

**What you can change:**
- Activity description
- Meeting schedule (days and/or times)
- Maximum number of participants
- Activity name

**What you'll provide:**
- Which activity to modify
- What needs to change (checkboxes)
- New information (only fill in fields for things you're changing)
- Reason for the change

**Example use case:**
> "Chess Club needs to move from Mondays to Thursdays because of a scheduling conflict, and we need to increase capacity from 12 to 15 students."

---

### 3. 👥 Manage Student Registrations

**When to use:** You need to add or remove students from activities.

**What you can do:**
- Add student(s) to an activity
- Remove student(s) from an activity
- Move student(s) between activities

**What you'll provide:**
- Action type (add, remove, or move)
- Activity name
- Student email address(es)
- Reason for the change
- Optional: Override capacity limits (when necessary)

**Example use cases:**
> "Add jane.doe@mergington.edu to Drama Club because she just joined the school."
> 
> "Remove john.smith@mergington.edu from Chess Club - he's switching to Programming Class instead."

---

### 4. 🐛 Report a Bug

**When to use:** Something isn't working correctly in the system.

**What you'll provide:**
- Description of the problem
- Which part of the system is affected (dropdown)
- Step-by-step instructions to reproduce the bug
- What should happen vs. what actually happens
- Any error messages you see
- How often it occurs

**Example use case:**
> "When I try to register a student for Chess Club, I get an error saying 'Authentication required' even though I'm logged in. This happens every time."

---

### 5. 🎨 UI/UX Improvement

**When to use:** You want to suggest improvements to how the website looks or works.

**Types of improvements:**
- Visual design (colors, fonts, styling)
- Layout/organization
- Navigation
- Accessibility
- Mobile responsiveness
- New features

**What you'll provide:**
- Type of improvement
- Which page or section
- Current situation
- What you'd like to see instead
- Why it's important
- Who benefits most

**Example use case:**
> "The activity cards all look the same. It would be helpful if academic activities had a blue color, sports had green, and arts had purple so students can quickly find what they're interested in."

---

## How to Submit an Issue

### Step 1: Go to the Issues Tab
Navigate to the GitHub repository and click on the "Issues" tab.

### Step 2: Click "New Issue"
You'll see a button that says "New Issue" - click it.

### Step 3: Choose Your Template
You'll be presented with the 5 templates described above. Click "Get started" on the one that matches your need.

### Step 4: Fill Out the Form
Complete all required fields (marked with a red asterisk *). The more detail you provide, the better!

### Step 5: Submit
Click "Submit new issue" at the bottom of the form.

### Step 6: Wait for Copilot
GitHub Copilot will be automatically assigned to your issue. It will:
1. Review your request
2. Create a plan
3. Implement the changes
4. Test the changes
5. Notify you when complete

---

## Tips for Success

### ✅ DO:
- **Be specific** - Provide exact names, times, and details
- **Explain why** - Help us understand the need behind your request
- **Include examples** - Real examples make it easier to understand
- **Check existing issues** - Make sure you're not duplicating a request

### ❌ DON'T:
- **Skip required fields** - We need all the information to help you
- **Be vague** - "Make it better" doesn't give us enough to work with
- **Submit duplicates** - Check if someone already requested the same thing
- **Include sensitive information** - Don't put passwords or private data in issues

---

## What Each Template Includes

Every template has been designed with four key components:

### 1. **Clear Problem Description**
Structured form fields that guide you to explain exactly what you need.

### 2. **Acceptance Criteria**
Built-in criteria that defines what success looks like, so you know what to expect.

### 3. **Implementation Hints**
Technical guidance for developers (or Copilot) on where to make changes, which files to modify, and what to consider.

### 4. **Context and Limitations**
Important information about how the system works and any constraints to be aware of.

---

## Example: Completed Template

Here's what a completed "Add New Activity" template might look like:

**Activity Name:** Photography Club

**Activity Description:** Learn digital photography techniques, photo composition, lighting, and editing using professional software. Students will work on projects and participate in a school photo exhibition.

**Activity Type:** Arts

**Meeting Days:** ☑️ Wednesday, ☑️ Friday

**Start Time:** 15:30

**End Time:** 17:00

**Maximum Participants:** 18

**Reason:** Several students have expressed interest in photography, and we have a teacher willing to supervise.

---

## Need Help?

If you're not sure which template to use or need assistance:

1. **Check the README** in the ISSUE_TEMPLATE folder
2. **Look at existing issues** for examples
3. **Ask in Discussions** if you have questions
4. **Contact IT support** for technical help

---

## Benefits of Using These Templates

✨ **For Teachers:**
- No coding knowledge required
- Simple, guided forms
- Faster request processing
- Clear expectations

✨ **For Students:**
- Quicker updates to activities
- Better system functionality
- More activities available

✨ **For Administrators:**
- Better organization of requests
- Tracking of changes
- Quality control

✨ **For Developers:**
- All necessary information in one place
- Consistent request format
- Automated assignment to Copilot
- Reduced back-and-forth communication

---

## Questions & Answers

**Q: What if I make a mistake in my issue?**
A: You can edit issues after submission. Just click "Edit" on your issue.

**Q: How long does it take for changes to be implemented?**
A: Simple requests may be completed in minutes. Complex changes may take longer. Copilot will keep you updated on progress.

**Q: Can I request something that's not in the templates?**
A: Yes! If none of the templates fit, you can still create a blank issue, but templates help ensure faster processing.

**Q: What if my request is urgent?**
A: Mark it as "High Priority" in the template and explain the urgency in the description.

**Q: Can I request multiple changes in one issue?**
A: It's better to create separate issues for different changes. This makes tracking and implementation easier.

---

## Technical Note for Developers

These templates are located in `.github/ISSUE_TEMPLATE/` and follow GitHub's issue form schema:
- `add-new-activity.yml` - For adding new activities
- `modify-activity.yml` - For modifying existing activities  
- `manage-registrations.yml` - For student registration management
- `bug-report.yml` - For reporting bugs
- `ui-ux-improvement.yml` - For UI/UX enhancement requests
- `config.yml` - Configuration for the template chooser
- `README.md` - Documentation for the templates

Each template auto-assigns to `@copilot` and includes structured fields, validation, and implementation guidance.
