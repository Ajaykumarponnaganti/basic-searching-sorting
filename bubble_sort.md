# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
PROCEDURE BubbleSort(arr, n)
        FOR i FROM 0 TO n - 2 DO
            FOR j FROM 0 TO n - i - 2 DO
                IF arr[j] > arr[j + 1] THEN
                    SWAP arr[j] WITH arr[j + 1]
                ENDIF
            ENDFOR
        ENDFOR
    END PROCEDURE
END
```
