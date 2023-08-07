Submissions: Aboud Dabbas, Angus Leung, Malhar Rajpal, Trung Nguyen 

Extension (SQL--)
    call "make clean; make" in ./ to generate sql executable
    run ./unit_tests in ./sql_files to run unit tests 

    run chmod +x testman.sh     (permissions)
    run chmod +x testgen.sh     (permissions)

    run ./testgen.sh in ./sql_files to run integration tests against Professor McBrien's SQL Database
    run ./testman.sh in ./sql_files to run integration tests against manually generated expected outputs

    sql.c in ./
    Other sql code files are in ./sql_files
    ./sql_files/integration_test_tables.txt is included for testman.sh to run integration tests

IF YOU WANT TO TRY SQL QUERIES FOR YOURSELF: 
    There is an example table data set ./USER_TEST_TABLE.txt 
    There is an example query          ./USER_TEST_QUERY.txt
    run "make clean; make" in ./
    run ./sql USER_TEST_TABLE.txt USER_TEST_QUERY.txt USER_TEST_RESULT.txt   in ./
    
    Look at the query result!

Enjoy!

