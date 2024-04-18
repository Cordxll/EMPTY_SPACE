# EMPTY_SPACE


=DATE(YEAR(TODAY()), 1, LEFT(A1, FIND(".", A1)-1)) + VALUE(MID(A1, FIND(".", A1)+1, LEN(A1)-FIND(".", A1)))-1


=DATE(
    IF(ISERR(FIND("/",A1)),
        RIGHT(A1,LEN(A1)-FIND(".",A1)),  -- if the date is in mm.dd format
        MID(A1,FIND("/",A1)+1,LEN(A1)))  -- if the date is in mm/dd/yyyy format

fid 39900000720654017
alp 953143415
we 5NH78686
