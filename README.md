# terraform-oci-8x8-iam

IAM module for OCI infrastructure (compartment, policies, groups)

This repo started as fork from https://github.com/oracle-terraform-modules/terraform-oci-iam
to address problem with usag of the "tenancy_ocid".

To allow to target any compartment other than "root" we need to introduce "target_compartment_ocid"
