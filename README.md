# Hybrid-Blockchain-Process-Flow-for-Testamentary-Records
Hybrid Blockchain Process Flow for Testamentary Records with E-Affidavit and Land Beneficiary Integration of a system and process flow for managing wills and land-beneficiary designations using blockchain technologies. 
The design integrates government e-affidavit platforms, permissioned distributed ledgers, off-chain permanent storage, public-chain anchoring, and smart-contract-driven access release triggered by verified death events.
Identity & Notarization: The testator executes a mini-will or land-beneficiary designation, digitally notarized via an e-affidavit platform, binding government ID and witness signatures.
On-chain Recordation: A hash of the notarized document, plus notarization metadata, is written to a permissioned ledger (e.g., Hyperledger Fabric).
Permanent Off-chain Storage: The full document is stored in Arweave/IPFS, with the hash pointer embedded in the ledger record.
Public Anchoring: At fixed intervals, a state hash of the permissioned ledger is anchored to a public chain (e.g., Polygon) for immutable timestamping.
Death Verification: A government-issued oracle supplies a signed proof of death to the smart contract.
Access Control & Key Management: Upon oracle verification, a threshold key-release protocol (KMS with multisig requirements) decrypts the off-chain testament document and grants access to designated beneficiaries.
Court Verification: Courts or land registries may verify chain-of-custody by comparing notarization metadata, hashes, and anchored proofs.
This disclosure publicly documents a combined process flow that integrates state-issued e-affidavits, notarization metadata, off-chain permanent storage, permissioned ledgers, and public-chain anchoring, specifically for testamentary documents and land-beneficiary designation in Lagos. This publication is intended to prevent future patenting of the same process by third parties.
