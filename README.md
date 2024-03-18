# FULL_ADDER
# Aim
To Study and verify Full adder using vivado.
# Apparatus Required
Personal computer with vivado software.
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)
# Program
~~~
module FULLADDER(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
wire w1,w2,w3;
xor g1(w1,a,b);
xor g2(sum,w1,c);
and g3(w3,a,b);
and g4(w2,w1,c);
and g5(carry,w2,w3);
endmodule
~~~
# Output
![image](https://github.com/karanpro06/FULL_ADDER/assets/119782103/6c274453-c1fa-4eae-aecb-53394787981f)
# Result
Hence Full adder is verified.

