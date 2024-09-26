# filegrep
find . -type f -name "*.py" -exec grep -Hn -i "search_string" {} \;
