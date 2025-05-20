start
:Input patient_name, doctor_name, date, time;
:create Appointment instance;
:set appointment_id = next_id;
:store in appointments dict;
:increment next_id;
:print confirmation message;
stop
