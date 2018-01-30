DO
BEGIN

 DECLARE v_index INT;
 DECLARE v_amount DECIMAL;

 v_index := 1;
 v_amount := 1000;
 FOR v_index IN 1..1000 DO

    INSERT INTO "LEOSYSTEM"."GitHub_POC::GITHUB_POC_TAB2" VALUES (v_index,'Row'||v_index, v_amount);
 	v_amount := v_amount * 1.0023 / 1.0017;	   
 END FOR;

END;
