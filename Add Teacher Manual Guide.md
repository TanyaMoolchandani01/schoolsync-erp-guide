****# Add Teacher Module - Manual Guide

## Overview
This comprehensive manual guide provides step-by-step instructions for adding a new teacher to the Edwyze School Management System. The Add Teacher module is a streamlined single-page form that captures all essential teacher information including personal details, contact information, designation, role association, and emergency contact details.

## Prerequisites
- Admin access to the Edwyze system
- Valid login credentials
- Access to the Team Management module

## Login Process

### Step 1: Access the System
1. Open your web browser and navigate to: `https://edwyze.com/login`
2. Enter your login credentials:
   - **Email**: Test2@gmail.com
   - **Password**: Test@123#
3. Click the "Sign in" button to access the admin dashboard

![Login Page](.playwright-mcp/login-page.png)

### Step 2: Navigate to Team Management
1. From the admin dashboard, locate the "Team" option in the left navigation menu
2. Click on "Team" to access the Team Management page

### Step 3: Access Teachers Section
1. On the Team Management page, you will see three options:
   - Teachers
   - Transportation
   - Other Staff
2. Click on "Teachers" to access the Teacher Management page

### Step 4: Access Add Teacher Module
1. On the Teacher Management page, click the "Add Member" button
2. This will open the Add Teacher form

![Teacher Management Page](.playwright-mcp/step-9-form.png.png)

---

## Add Teacher Process

### Form Overview
The Add Teacher form is a comprehensive single-page form that includes the following sections:

1. **Profile Image Upload** (Optional)
2. **Personal Information**
3. **Employment Details**
4. **Contact Information**
5. **Emergency Contact Information**

![Add Teacher Initial Form](.playwright-mcp/step-10-form.png.png)

![Add Teacher Initial Form](.playwright-mcp/step-11-form.png.png)


### Step 1: Profile Image Upload (Optional)

**Purpose**: Upload a profile picture for the teacher

**Instructions**:
1. Click on the "Upload" button in the Profile Image section
2. Select an image file from your computer
3. **File Requirements**:
   - Maximum file size: 5MB
   - Supported formats: JPG, PNG
4. The image will be displayed once uploaded

### Step 2: Personal Information

**Purpose**: Capture basic personal information about the teacher

**Required Fields**:
- First Name *
- Last Name *
- Employee ID *

**Optional Fields**:
- Middle Name

**Instructions**:
1. **First Name**: Enter the teacher's first name (e.g., "Sarah")
2. **Middle Name**: Enter middle name if applicable (e.g., "Elizabeth")
3. **Last Name**: Enter the teacher's last name (e.g., "Johnson")
4. **Employee ID**: Provide a unique employee ID (e.g., "TCH2025001")

### Step 3: Employment Details

**Purpose**: Assign designation and role association

**Required Fields**:
- Designation *
- Role Association *

**Instructions**:
1. **Designation Selection**:
   - Click on the "Select designation..." dropdown
   - Choose from available options:
     - Principal
     - Vice Principal
     - Head of Department
     - Senior Teacher
     - Teacher
     - Assistant Teacher
     - Coordinator
     - Administrator
     - Driver
     - Bus Monitor
     - Maintenance Staff
     - Security Guard
     - Librarian
     - Counselor
     - ⊕ Create New Designation (to add custom designation)

2. **Role Association Selection**:
   - Click on the "Select a role" dropdown
   - Choose from available roles:
     - PRINCIPAL
     - TEACHER
     - FEES_ADMIN
     - HELP_SUPPORT
     - Teachers
     - Single_permission
     - cp

### Step 4: Contact Information

**Purpose**: Capture email and phone contact details

**Required Fields**:
- Email *
- Joining Date *

**Optional Fields**:
- Contact Number

**Instructions**:
1. **Email Address**: Enter a valid email address (e.g., "sarah.johnson@edwyze.com")
   - Note: Login credentials will be automatically sent to this email address
2. **Contact Number**: Enter phone number (10 digits required, e.g., "9876543210")
3. **Joining Date**: Select the teacher's joining date (e.g., "2025-01-15")

### Step 5: Emergency Contact Information

**Purpose**: Capture emergency contact details for the teacher

**Required Fields**:
- Contact Name *
- Relation *
- Contact Number *

**Instructions**:
1. **Emergency Contact Name**: Enter full name (e.g., "Robert Johnson")
2. **Relationship**: Select relationship from dropdown:
   - Father
   - Mother
   - Grandfather
   - Grandmother
   - Uncle
   - Aunt
   - Guardian
   - Other
3. **Emergency Contact Number**: Enter phone number (10 digits required, e.g., "9876543211")

### Step 6: Form Submission

**Instructions**:
1. **Review**: Double-check all entered information for accuracy
2. **Submit**: Click the "Submit" button to complete the teacher registration
3. **Cancel**: Click "Cancel" to discard changes and return to the teachers list


### Step 7: Confirmation

**Success Message**: Upon successful submission, you will see:
- A success message: "Teacher added successfully"
- The teacher will appear in the teachers list with all provided information

![Add Teacher Success](.playwright-mcp/step-12-form.png.png)

---

## Form Validation

### Required Field Validation
- All fields marked with asterisk (*) are mandatory
- Form submission will be blocked if required fields are empty
- Error messages will appear for incomplete required fields

### Data Format Validation
- **Email**: Must be in valid email format (user@domain.com)
- **Phone Numbers**: Must be exactly 10 digits
- **Employee ID**: Must be unique across the system
- **Joining Date**: Must be a valid date

### File Upload Validation
- **Profile Image**: Maximum 5MB, JPG/PNG formats only
- **File Size**: System will reject files larger than 5MB
- **Format**: Only JPG and PNG images are accepted

---

## Best Practices

### Data Entry
1. **Accuracy**: Double-check all entered information for accuracy
2. **Completeness**: Fill in all required fields before submitting
3. **Consistency**: Ensure data consistency across all fields
4. **Validation**: Verify email addresses and phone numbers

### Employee ID Management
1. **Uniqueness**: Ensure each employee ID is unique
2. **Format**: Use consistent naming convention (e.g., TCH + year + sequential number)
3. **Documentation**: Keep record of assigned employee IDs

### File Uploads
1. **Format**: Use only supported file formats (JPG, PNG)
2. **Size**: Keep file sizes under 5MB
3. **Quality**: Ensure images are clear and professional
4. **Naming**: Use descriptive file names for easy identification

### Security
1. **Privacy**: Ensure teacher data is handled confidentially
2. **Access**: Only authorized personnel should access teacher information
3. **Backup**: Regular backups of teacher data are recommended

---

## Troubleshooting

### Common Issues

**Issue**: Cannot submit the form
- **Solution**: Check that all required fields are filled
- **Solution**: Verify that dropdown selections are made
- **Solution**: Ensure phone numbers are exactly 10 digits

**Issue**: File upload fails
- **Solution**: Check file size (must be under 5MB)
- **Solution**: Verify file format (JPG, PNG only)

**Issue**: Email validation error
- **Solution**: Ensure email format is correct (user@domain.com)
- **Solution**: Check for typos in email address

**Issue**: Phone number validation error
- **Solution**: Use exactly 10 digits (no spaces or special characters)
- **Solution**: Remove country codes if included

**Issue**: Employee ID already exists
- **Solution**: Use a different, unique employee ID
- **Solution**: Check existing employee IDs in the system

### Support
- Contact system administrator for technical issues
- Refer to system documentation for advanced features
- Check system status if experiencing connectivity issues

---

## Additional Features

### Create New Designation
If the required designation is not available in the dropdown:
1. Click on "⊕ Create New Designation" in the designation dropdown
2. Fill in the designation name and description
3. Click "Add Designation" to create and select the new designation

### Role Management
- Role associations determine system access permissions
- Choose appropriate role based on teacher's responsibilities
- Contact administrator for custom role creation

### Email Notifications
- Login credentials are automatically sent to the provided email address
- Ensure email address is valid and accessible
- Check spam folder if credentials are not received

---

## Conclusion

The Add Teacher module provides a streamlined and user-friendly interface for registering new teachers in the Edwyze School Management System. Unlike the multi-step Add Student process, the Add Teacher module uses a single comprehensive form that efficiently captures all necessary teacher information.

The system ensures data integrity through validation, provides flexibility with optional fields, and maintains a consistent user experience. The automatic email notification feature ensures teachers receive their login credentials promptly.

For additional support or advanced features, please refer to the system documentation or contact the technical support team.

---

**Document Version**: 1.0  
**Last Updated**: January 2025  
**System**: Edwyze School Management System  
**Module**: Add Teacher

