#!/bin/sh
# simulate tests: exit 0 = pass, exit 1 = fail
echo "Running fake unit tests..."
sleep 1
echo "1 test passed" > test-results.txt
echo "Tests finished"
exit 0
