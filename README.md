**Digital Forensic Investigation Project**

**Overview**

This project demonstrates a complete end-to-end digital forensic investigation carried out in a controlled environment using industry-standard tools and methodologies.
It follows a structured forensic process including -

⦁	Evidence identification and preservation
⦁	Forensic imaging
⦁	Deleted file recovery
⦁	Browser history examination
⦁	Metadata extraction
⦁	Documentation (Evidence Form, Chain of Custody, Log Sheet, Forensic Report)

The project simulates a real-world cyber incident where a suspect virtual machine is examined using professional forensic tools.

**Project Objectives**

⦁	Apply standard forensic procedures from acquisition to reporting
⦁	Use multiple forensic tools to extract, preserve, and analyze digital evidence
⦁	Recover deleted images and analyze browsing activities
⦁	Extract file metadata for investigative analysis
⦁	Produce professional forensic documentation
⦁	Demonstrate compliance with legal & ethical forensic guidelines

Tools Used -

FTK Imager -	Create forensic disk image, verify hash values
OSFMount - Mount forensic image safely in read-only mode
Browser History Examiner -	Analyze browser activity & timeline
ExifTool -	Extract metadata from image files
Autopsy (Optional) -	File system analysis & recovery

**Investigation Workflow**

Phase 1 – Suspected Machine Creation

⦁	Created a virtual machine (Windows).
⦁	Visited multiple websites and downloaded images.
⦁	Stored all files in a folder renamed with my EID.
⦁	Permanently deleted the images.
⦁	Shut down the VM (evidence source).

Phase 2 – Forensic Workstation & Investigation

A separate forensic workstation was set up with FTK Imager, OSFMount, ExifTool, and Browser History Examiner.

Tasks Performed -

⦁	Created a bit-for-bit forensic image of the suspect VM disk
⦁	Verified integrity using MD5/SHA-1 hashing
⦁	Mounted the forensic image in read-only mode
⦁	Recovered deleted images from file system
⦁	Extracted metadata (timestamps, camera/device info, geolocation where available)
⦁	Analyzed browser activity to track visited websites, download patterns, and user behavior

Phase 3 – Documentation Created

This project includes custom-created original documents (not assignment text):

⦁	Evidence Form
⦁	Chain of Custody Form
⦁	Investigation Log Sheet
⦁	Forensic Analysis Report

All documents strictly follow professional forensic documentation standards.

**Key Findings Summary**

(Replace this with your actual findings)
Example structure:

⦁	Recovered X deleted images from unallocated space
⦁	Browser history showed visits to these domains:
          example.com
          imagesite.net
⦁	Metadata extracted included:
          EXIF timestamps
          Device type / software used
          File modification patterns
⦁	Timeline confirmed activity leading to deletion event


Project File Structure

A recommended GitHub repository structure:

📁 forensic-investigation-project
│
├── README.md
│
├── /screenshots
│     ├── ftk-imager.png
│     ├── osfmount.png
│     ├── recovered-images.png
│     ├── browser-history.png
│     ├── exiftool-output.png
│
├── /documentation
│     ├── evidence-form.pdf
│     ├── chain-of-custody.pdf
│     ├── investigation-log.pdf
│     ├── forensic-report.pdf
│
└── /findings
      ├── recovered-files/
      ├── metadata-output/

**Skills Demonstrated**

⦁	Forensic imaging and evidence preservation
⦁	Hash verification & integrity validation
⦁	Deleted data recovery
⦁	Browser artifact investigation
⦁	File metadata analysis
⦁	File system understanding (allocated vs unallocated)
⦁	Formal forensic documentation
⦁	Legal & ethical forensic compliance
⦁	Report writing and professional communication

**Legal & Ethical Considerations**

This project follows:

⦁	NIST forensic process model
⦁	ISO/IEC 27037 guidelines
⦁	Principles of evidence integrity, chain of custody, and proportional investigation
⦁	Ethical handling of data during forensic analysis

All investigations were conducted in a simulated environment using non-sensitive data.

**Conclusion**

This project highlights my developing skills in digital forensics and cybersecurity. By completing a full investigation workflow—from imaging and analysis to reporting—I demonstrated practical competence with forensic tools and methodologies.
This work strengthens my portfolio as a student preparing for future opportunities in cybersecurity, digital forensics, and related technical fields.
