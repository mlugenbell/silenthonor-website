# Test Credentials

## Admin Account
- Email: admin@silenthonor.org
- Password: SilentHonor2024!
- Role: admin

## Test Member Account (if created)
- Register through /signup.html with any email

## Auth Endpoints
- POST /api/auth/register - Create new account
- POST /api/auth/login - Login with credentials
- POST /api/auth/logout - Logout (clears cookies)
- GET /api/auth/me - Get current user info
- POST /api/auth/refresh - Refresh access token
- POST /api/auth/forgot-password - Request password reset
- POST /api/auth/reset-password - Reset password with token

## Admin Endpoints
- GET /api/admin/members - List all members
- GET /api/admin/members/{id} - Get member details
- GET /api/admin/dd214/{filename} - View DD-214 file
- POST /api/admin/members/{id}/verify - Approve/reject member
- GET /api/admin/contacts - List contact submissions
- GET /api/admin/stats - Dashboard statistics

## File Upload
- POST /api/upload/dd214 - Upload DD-214 document (requires auth)

## Contact
- POST /api/contact - Submit contact form (no auth required)
