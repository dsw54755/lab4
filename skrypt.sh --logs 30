num_files=${1:-30}
for ((i=1; i<=$num_files; i++)); do
    echo "Nazwa pliku: log$i.txt" > "log$i.txt"
    echo "Nazwa skryptu: $0" >> "log$i.txt"
    echo "Data utworzenia: $(date)" >> "log$i.txt"
done
echo "Utworzono $num_files plików logowych."
