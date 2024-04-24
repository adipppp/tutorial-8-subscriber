# tutorial-8-subscriber

## Reflection 1a
AMQP stands for Advanced Message Queuing Protocol. It is an open standard protocol for message-oriented middleware, enabling the systems to communicate with each other via messaging. AMQP defines a set of rules for systems to follow so they can communicate and exchange messages, regardless of the underlying platform or language.

AMQP is commonly used in enterprise environments where different systems, possibly written in different programming languages or running on different platforms, need to communicate reliably and efficiently. It competes with other messaging protocols and standards such as MQTT, which is typically lighter and more suited for IoT devices, and JMS (Java Message Service), which is specific to Java environments.

## Reflection 1b
The first part of the URI, "guest:guest", defines username and password. In this case, the "guest" before the colon (:) is the username and the "guest" after the colon is the password. Moving to the second part of the URI, "localhost" defines the hostname or IP address while the integer after the colon (:) to the right of it defines the port where the AMQP server is running.
