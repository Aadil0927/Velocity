## MonitorMe
by <img src="resources/images/velocity.png" width="90" height="30">

### Table of Contents

- Overview
- Mission
- User Journey
- 

## Overview
  **MonitorMe** is a new patient monitoring product from Stayhealthy Inc. This document describes high-level architecture of MonitorMe’s local-standalone IT infrastructure in hospitals. It documents key requirements and features extracted from clients requirements and research on similar products on market. A software and hardware architecture that satisfies these requirements is presented in this document.

## Mission
  Stay Health Inc. is on a long journey to provide End to End support for hospitals. The company already has a two popular SaaS application **MonitorThem** and **MyMedicalData** in the market. **MonitorMe** aims to close the gap between Cloud based Saas applications to inhouse patient monitoring requirements. 

## User Journey
  **MonitorMe** has two unique user groups/Actors.
  1. Nurse Station Users / **Kiosk User**
       This user monitors patients on a monitoring screen set up at each nurses station.
       ### Nurse Station Users journey
         * User logs in to Kiosk
         * User observes the patient's vitals which rotate every every 5 seconds
         * User can review history and filter patient vitals through filters
         * User can generate holistic snapshot for a patient and upload it to 'MyMedicalData'
      
  2. On the go Users / **Mobile Users**
       This user monitors patients patients through a Push notification on a mobile app.
       ### Mobile Users Journey
         * User downloads and registers through mobile app
         * User receives alerts through push notification

## Requirements
  The architecture for **MonitorMe** must support the below requirements

  ### 1. Availability
  
     
