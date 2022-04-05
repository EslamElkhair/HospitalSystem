# Hospital Management System

**Hospital management system is a console-based application used to help doctors to manage the process of ckecking patients regularly.** 

**The System is working as following:** 

* There are 20 different specialization in the system (e.g. Children, Surgery,etc)

* For each specialization, there are only 5 available spots (queue)

**The user has the following options:** 

* Adding a patient

  * the system Reads the requested specialization (1 - 20)

  * the system Reads patient's name and status (0 = regular, 1 urgent)

  * the system doesn't accept over than 5 patients per specialization.

  * If the user is regular, add in end of queue. Otherwise, add in Begin

* Print patients List for the specializations that have waiting patients

* Dr can pickup a patient
  
  * the system Read the requested specialization. If no patients, it informs the doctor

  * Otherwise, the system ask the patient to go with the Dr. tnen it Removes the picked patient from the queue
 
