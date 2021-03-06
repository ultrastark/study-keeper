# Changelog
## v1.0.0 : 2020-06-26
 ### Add
 - admin/tasks 
   - import and export as JSON
 ### Enhance
 - global
   - text

## v0.2.11 : 2020-06-16
 ### enhance
  - admin/studies
    - remove download-button on emtpy study
    
 ### fix    
   - global 
     - Some text issues
   - participant
     - send the content of the question

## v0.2.8 : 2020-06-10
 ### add
  - admin/study
    - lock study
  - admin/users
    - warning on role change
 ### enhance
  - participant/result-screen 
    - add loader
    
## v0.2.7 : 2020-05-23
 ### enhance
  - participant/tasks
    - Responsiveness
 
 ### fix
  - participant/tasks
    - Save properly difficulty between training sessions
    
## v0.2.6 : 2020-05-14
 ### enhance
  - participant/participant
    - Show already completed exercices in the actual trainingSession
    
## v0.2.5 : 2020-05-08
 ### add
  - organisation/user
    - let user have different role on different organisation 

 ### enhance
  - admin/study
    - Let the user set an interval of 0

 ### fix
  - admin/user
    - on delete from an organisatin only remove the acces
    - enhance user change or deleting access to another user (depending on the user role

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
