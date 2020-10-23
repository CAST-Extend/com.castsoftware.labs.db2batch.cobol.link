# com.castsoftware.labs.db2batch.cobol.link

Create between JCL step and Cobol DB2 program executed using DB2BATCH.

Sample JCL Step syntax:

//GSPSLS50 EXEC PGM=COSUTILR,
//            COND=(8,LE),
//            DYNAMNBR=20,
//            PARM=(IKJEFT01,0EQ,2020,
//            '%DB2BATCH GCCE561 &PLAN0N &DB2HLQ')
