# ubi-persistent

Red Hat UBI Sample app that persists data to a PVC

## Setup

- Clone this repo to get started:

  1. `git clone https://github.com/tkagn/ubi-persistent.git` 
  2. `cd .\ubi-persistent.git`

- Apply manifest to cluster

   3. `oc apply -k <desired deployment>`

       - ubi - UBI container with PVC backed by default storage class
       - ubi-rbd - UBI container with PVC backed by RHODF RBD storage class
       - ubi-cephfs - UBI container with PVC backed by RHODF CephFS storage class




      

