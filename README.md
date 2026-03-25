# Linux-System-Administration-User-Group-Management
## Overview
This project demonstrates basic Linux system administration tasks using Fedora.

## Tasks Performed
- Created and managed users
- Set and updates passwords
- Locked and unlocked user accounts
- Created and managed groups
- Added users to groups
- Verified user and group information

  ## Steps performed
  ### 1. Create a user
  sudo useradd -m testuser

  ### 2. Set Password
  sudo passwd testuser

  ### 3. Check User information
  id testuser

  ### 4. Create a Group
  sudo groupadd testgroup

  ### 5. Add user to Group
  sudo usermod -aG testgroup testuser

  ### 6. Verify GroupMembership
  groups testuser

  ### 7. Lock User Account
  sudo passwd -l testuser

  ### 8. Unlock user Account
  sudo passwd -u testuser

  ### 9. Delete User
  sudo userdel testuser

  ### 10. Delete Group
  sudo groupdel testgroup

  ## Tools used
  -Fedora Linux
  -Terminal

  ## Purpose
  This project helped me build foundationalLinux skills requiredfor IT Help Desk and system administration roles.

  Code
  ## Screenshots
  ### User & Group Management
  ! [User Management](linux identity manm pic.jpg)
  ! [Group Management] (linux identy manem pic 2.jpg)

  
  
