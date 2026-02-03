Interger data type :
Sometimes, a number isn't a "math" object; it is a name or a label. In networking, we use integers to uniquely identify specific 
parts of the network. We rarely do math on these (you wouldn't multiply a VLAN ID by 5). instead, we check if they match a specific value.

config_vlan_id = 10
target_vlan_id = 20

floating point :
here we all most check utilization of device or we check the speed of packet transfer or realtime network speed .
  cpu_utilization = 35.5 
  memory_utilization = 12.7

few basic math opration :

 1.Multiplication (*)
This usually results in an Integer if both numbers are integers.
Scenario: You have 10 packets, and each takes 2 ms to process. How long does it take total?
time_per_packet = 2      # int
no_of_packets = 10       # int

# Logic: Total Time = Time per Unit * Count
total_processing_time = time_per_packet * no_of_packets

print(total_processing_time)
# Output: 20
# Type: int

2.Division (/)
This is the special one. In Python, standard division always creates a Float, even if the numbers divide evenly!

Scenario: You transferred 100 MB of data in 8 seconds. What is the speed?

total_data = 100    # int
duration = 8        # int

# Logic: Speed = Amount / Time
speed = total_data / duration

print(speed)
# Output: 12.5
# Type: float (Notice the decimal point!)

3. Addition (+) & Subtraction (-)
These keep the type of the numbers involved. If you add two ints, you get an int.

Scenario: You received 500 packets on Port A and 200 on Port B.
port_a_count = 500
port_b_count = 200

total_packets = port_a_count + port_b_count
# Output: 700 (int)




