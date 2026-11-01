╔═══════════════════════════════════════════════════════════════════════════════╗
║                    CLASSROOM MONITORING PLATFORM                              ║
║                      Real-time Classroom Management                           ║
╚═══════════════════════════════════════════════════════════════════════════════╝

┌─────────────────────────────────────────────────────────────────────────────┐
│                           GROUP MEMBERS                                      │
├─────────────────────────────────────────────────────────────────────────────┤
│  No. │ Full Name              │ ID Number          │ Section               │
├─────────────────────────────────────────────────────────────────────────────┤
│  1   │ Zewde Bekele           │ UGR/188847/6       │ 2                     │
│  2   │ Aklilu Tesfay          │ UGR/187845/16      │ 1                     │
│  3   │ Rediet Tsegay          │ UGR/188595/16      │ 1                     │
│  4   │ Sbhat G/Egzabher       │ UGR/188642/16      │ 1                     │
│  5   │ Kalid Jibril           │ UGR/188299/16      │ 1                     │
│  6   │ Mulugeta Berhe         │ UGR/188509/16      │ 1                     │
│  7   │ Firaol Idris           │ UGR/188127/16      │ 1                     │
│  8   │ Hagazi Berhe           │ UGR/189722/16      │ 2                     │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│                          FILES IN THIS PACKAGE                               │
├─────────────────────────────────────────────────────────────────────────────┤
│  📁 File Name              │ Description                                     │
├─────────────────────────────────────────────────────────────────────────────┤
│  ServerMain.java          │ Teacher Dashboard - Main server application    │
│  StudentClientFX.java     │ Student Portal - Client application            │
│  java_documentation.pdf   │ Complete project documentation                 │
│  database_setup.sql       │ Database schema and SQL commands               │
│  README.txt               │ This file - instructions                       │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│                          INSTALLATION STEPS                                  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  STEP 1: CHANGE DATABASE PASSWORD                                           │
│  ─────────────────────────────────────────────────────────────────────────  │
│  ⚠️ IMPORTANT! In BOTH Java files, find:                                    │
│                                                                              │
│     private static final String PASSWORD = "@Aklil19";                      │
│                                                                              │
│     CHANGE to YOUR PostgreSQL password:                                     │
│                                                                              │
│     private static final String PASSWORD = "your_password_here";            │
│                                                                              │
│  STEP 2: SETUP DATABASE                                                     │
│  ─────────────────────────────────────────────────────────────────────────  │
│  Run the SQL commands in database_setup.sql file                            │
│                                                                              │
│  STEP 3: ADD JDBC DRIVER                                                    │
│  ─────────────────────────────────────────────────────────────────────────  │
│  Download: https://jdbc.postgresql.org/download/postgresql-42.7.1.jar       │
│  Add to project Libraries in NetBeans                                       │
│                                                                              │
│  STEP 4: RUN THE PROJECTS                                                   │
│  ─────────────────────────────────────────────────────────────────────────  │
│  Teacher: Run ServerMain.java → Click "Start Server"                        │
│  Student: Run StudentClientFX.java → Login/Register                         │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│                          TEST ACCOUNT                                        │
├─────────────────────────────────────────────────────────────────────────────┤
│  Username: teststudent                                                      │
│  Password: password                                                         │
└─────────────────────────────────────────────────────────────────────────────┘

╔═══════════════════════════════════════════════════════════════════════════════╗
║                    END OF README                                              ║
╚═══════════════════════════════════════════════════════════════════════════════╝
