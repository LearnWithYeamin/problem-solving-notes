ESP8266 এর জন্য আলাদা board manually install করতে হয়। নিচের স্টেপগুলো ঠিকভাবে ফলো করেন:
১. File > Preferences এ গিয়ে Board Manager URLs এর ঘরে নিচের লিংকটি এড করেন:
https://arduino.esp8266.com/.../package_esp8266com_index...
এবং Editor Quick Suggestions অপশনটি টিক মার্ক দিয়ে OK প্রেস করেন।
২. তারপর Tools > Board > Board Manager এ গিয়ে esp8266 লিখে সার্চ করে ESP8266 by ESP8266 Community board টি ইনস্টল করেন।
৩. তারপর আপনার ESP8266 বোর্ডটি USB দিয়ে পিসিতে কানেক্ট করেন।
৪. এরপর Select Board > Select Other Board & Port এ গিয়ে আপনার ESP8266 বোর্ড এবং USB পোর্টটি সিলেক্ট করেন।
এরপর কোড করলে সাজেশন আসবে সঠিকভাবে।