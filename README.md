GNS3-FDR2019-1
El proyecto subido esta como se muestra en el video explicativo:
https://youtu.be/PGQXqMt9N40

Para realizar los cambios vistos en la segunda parte del video, pueden usarse como referencia:
R1:
configure terminal
ip route 10.11.17.0 255.255.255.0 10.11.13.2
end
wr

R2:
configure terminal
ip route 10.11.17.0 255.255.255.0 10.11.14.1
end


configure terminal
ip route 10.11.12.0 255.255.255.0 10.11.13.1
end
wr

R3:
configure terminal
ip route 10.11.12.0 255.255.255.0 10.11.14.2
end
wr

