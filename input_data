.data
input db 255,0

.code
main proc
    mov edx, 255
    mov ecx, offset input
    mov ebx, 0
    mov eax, 3
    int 0x80
    
    mov edx, 255
    mov ecx, offset input
    mov ebx, 1
    mov eax, 4
    int 0x80
    
    mov eax, 1
    int 0x80
main endp
end main