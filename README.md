# Uncommon Error in Python Function: ZeroDivisionError with Both Inputs Zero

This repository demonstrates a scenario where a Python function encounters an uncommon error due to edge case handling with inputs equal to zero. The function intends to handle zero inputs gracefully, but it fails in the specific case where both inputs are 0, resulting in an unexpected error.

## Bug Description:

The `function_with_uncommon_error` function is designed to avoid ZeroDivisionError by checking inputs but fails to handle the case when both are zero. This leads to unexpected behavior that can be difficult to catch during testing if not explicitly addressed. The problem is a combination of conditions and error handling, making it slightly uncommon.

## Solution:

The provided solution enhances the function to explicitly check for the case where both inputs are zero and returns an appropriate value (0 in this case), effectively preventing the ZeroDivisionError.