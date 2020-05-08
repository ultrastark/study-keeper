# Changelog
## v0.2.5 : 2020-05-08
 ### fix
  - admin/user
    - on delete from an organisatin only remove the acces
    - enhance user change or deleting access to another user (depending on the user role)

## v0.2.2 : 2020-05-03
### enhance
  - core/angular
    - update from v8.0 to v9.0
  - bit/us-swiper
    - update from v0.0.7 to v0.2 (use of the new angular compiler)
  - admin/tasks
    - better auto naming logic
 
 ### fix
  - admin/study
    - save on reorder trainingSession

## v0.2.1 : 2020-05-01
### fix
  - admin/tasks
    - save change on edit

## v0.2.0 : 2020-04-29

### add
  - admin/study
      - edit training session within the study
      - remove participents
      - autosave change
  
### enhance
  - admin/study
      - on create a new study, directly save it into the database
      - better add, remove researcher and participent logic
### fix
  - admin/studies : download
      - disable downlaod on empty study
      
  - global : sidenav
      - keep current sidebar highlighted on reload 
      
## v0.1.9 : 2020-04-27

### add
  - admin
      - alpha banner
      - navbar labels
  
  - participant
      - between tasks results
