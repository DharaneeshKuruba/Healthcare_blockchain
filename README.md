# Healthcare_blockchai

A Solidity smart contract that manages patient healthcare records with strict access control.

## Features

- Admin role: The contract deployer is the admin who can add or remove doctors.
- Doctor role: Only doctors can add patient records.
- Patient records: Records store a timestamp, data hash (e.g., IPFS), and the doctor who added it.
- Access control: Patients can grant or revoke access to their records for specific viewers.
- Audit logging: Events are emitted when records are added or access rights change.
- Secure viewing: Only the patient, authorized viewers, or doctors can view patient records.

## Usage

- Admin adds/removes doctors.
- Doctors add new records for patients.
- Patients control who can view their records.
- Records can be fetched only by authorized users.

This contract ensures privacy, traceability, and controlled access to sensitive healthcare data on the blockchain.
