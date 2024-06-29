# jar-project
כתיבת קבצי פרוייקט ה-jar
<img width="453" alt="Screenshot 2024-06-29 at 13 59 49" src="https://github.com/darkt2003/jar-project/assets/162579939/35ce82b3-2f23-412e-a824-b5bb5890e78e">

קוד בסיסי ב-java ו-maven ויצירת jar


<img width="591" alt="Screenshot 2024-06-28 at 14 27 54" src="https://github.com/darkt2003/jar-project/assets/162579939/f2f48520-fbdd-44bf-8142-751e1ce64278">

יצירת dockerfile

<img width="471" alt="Screenshot 2024-06-29 at 14 05 08" src="https://github.com/darkt2003/jar-project/assets/162579939/245724d6-662a-455e-a603-b592d2507897">

שימוש ב-docker build ו-docker run

<img width="1153" alt="Screenshot 2024-06-29 at 14 08 44" src="https://github.com/darkt2003/jar-project/assets/162579939/c3b7e5ad-e05e-42f2-ba02-6335e5313294">

לדחוף את ה-docker ל-repository ב-docker hub

<img width="105" alt="Screenshot 2024-06-29 at 14 11 12" src="https://github.com/darkt2003/jar-project/assets/162579939/1e49ebbb-b88b-425e-9f50-7a2559791d84">

<img width="341" alt="Screenshot 2024-06-29 at 14 12 32" src="https://github.com/darkt2003/jar-project/assets/162579939/00fca0f8-7176-4194-b1c5-426be20c3f5c">

<img width="341" alt="Screenshot 2024-06-29 at 14 12 57" src="https://github.com/darkt2003/jar-project/assets/162579939/f13dcd48-4298-4f8b-a840-07768e67fbcf">

<img width="671" alt="Screenshot 2024-06-29 at 14 13 59" src="https://github.com/darkt2003/jar-project/assets/162579939/dbbb7327-2f28-4544-bcbc-cd8e6380089a">

משימה 2: 
התקנת jenkins (התקנה מהאתר הרשמי של jenkins)

<img width="253" alt="Screenshot 2024-06-29 at 14 16 32" src="https://github.com/darkt2003/jar-project/assets/162579939/115c7b19-2a65-49df-9f9d-f4cf58a85a6b">


התחברות ל-jenkins על localhost:

<img width="1050" alt="Screenshot 2024-06-28 at 16 50 27" src="https://github.com/darkt2003/jar-project/assets/162579939/890814f9-449c-4556-8f95-e3b2635dfe70">

יצירת CI pipeline:

<img width="1437" alt="Screenshot 2024-06-28 at 16 58 20" src="https://github.com/darkt2003/jar-project/assets/162579939/7611a74b-72c0-4f72-a8dd-ac84fc65628f">


כתיבת הסקריפט המתאים ל-pipeline והרצה שלו:

<img width="1062" alt="Screenshot 2024-06-29 at 01 25 24" src="https://github.com/darkt2003/jar-project/assets/162579939/22908d4d-56fa-4984-b783-8665f622787c">

<img width="666" alt="Screenshot 2024-06-29 at 01 26 24" src="https://github.com/darkt2003/jar-project/assets/162579939/5d10db41-9a67-4d08-9e8e-4bf3fc2a8f32">


כתיבת הסקריפט המתאים ל-cd pipeline והרצה שלו:

<img width="942" alt="Screenshot 2024-06-29 at 13 50 00" src="https://github.com/darkt2003/jar-project/assets/162579939/ab1e09a3-c6b2-4494-b105-374af3d2c8f9">

משימה 4:
קובץ הסבר על כל שלב ב-ci 
<img width="854" alt="Screenshot 2024-06-29 at 14 44 59" src="https://github.com/darkt2003/jar-project/assets/162579939/950cc135-ace9-4f6f-925f-73309dcea37d">

שלב זה עושה checkout לרפוזיטורי ב-git ומשתמש ב-credentials ששמורים ב-credentials כדי להתחבר ל-git 

<img width="321" alt="Screenshot 2024-06-29 at 14 50 29" src="https://github.com/darkt2003/jar-project/assets/162579939/9d961c99-83b9-4b52-8780-69cbd1192c77">

שלב זה בונה את הפרוייקט maven מתוך ה-javaProject.
ה-dir מציין את המיקום שממנו הפעולות יתבצעו.
התקנה של כלי mvn ומחיקה של הקימפול הקודם שהתבצע כדי שיהיה אפשר לבצע קומפילציה מחדש בשביל הפרויקט. 


<img width="329" alt="Screenshot 2024-06-29 at 14 58 45" src="https://github.com/darkt2003/jar-project/assets/162579939/03aaf9df-6b01-44d8-822e-546d92c57467">

שלב זה מפעיל את הבדיקות לפרוייקט שוב מוחק קבצי קומפילציה ישנים ואז מריץ בדיקות

קובץ הסבר על כל שלב ב-cd:

<img width="492" alt="Screenshot 2024-06-29 at 15 02 21" src="https://github.com/darkt2003/jar-project/assets/162579939/3d9face4-68cf-48dd-9de8-75130955f9a7">

הגדרת משתני סביבה שנוכל להשתמש בהם לכל אורך ה-script

<img width="856" alt="Screenshot 2024-06-29 at 15 04 08" src="https://github.com/darkt2003/jar-project/assets/162579939/350cfe4c-429b-4e3d-849c-229cfaa32547">

התחברות ל-docker hub באמצעות ה-credentials שנשמרו ב-jenkins

<img width="508" alt="Screenshot 2024-06-29 at 15 05 26" src="https://github.com/darkt2003/jar-project/assets/162579939/d6b9cec2-8aa1-4a5a-9c8d-d8320c391a38">

מתוך ה-docker hub repository לעשות docker pull ל-image המתאים שהועלה לשם.

<img width="668" alt="Screenshot 2024-06-29 at 15 07 58" src="https://github.com/darkt2003/jar-project/assets/162579939/1fedd54b-4280-4c42-921c-e1021ea3fc90">

פריסה של סביבת בדיקה. ראשית, לנקות כל קונטיינר אחר שרץ כדי לאפשר סביבה נקייה. ואז מריץ דוקר חדש ומציין באיזה פורטים.

<img width="728" alt="Screenshot 2024-06-29 at 15 12 15" src="https://github.com/darkt2003/jar-project/assets/162579939/52423b49-a04d-4f91-a2ec-d5acda1a5a5c">

ולבסוף הפעלת בדיקות. שומר את ה-exit code שהופעל במהלך הריצה של הקונטיינר ובודק האם היו שגיאות. 

<img width="434" alt="Screenshot 2024-06-29 at 15 14 39" src="https://github.com/darkt2003/jar-project/assets/162579939/81b8d964-2f3b-4b8d-b502-2013377ec75b">

ואחרי שכל הבדיקות הסתיימו, לנקות את סביבת העבודה, והדפסת הודעה מתאימה

הכלים והטכנולוגיות שהשתמשתי בהם: intellij, docker, jenkins, git...


כיצד ניתן לפתור בעיות שעלולות לצוץ בזמן ריצה של ה-pipeline?
תשובה: יכולות לצוץ בעיות בכל אחד מהשלבים ואפשר לדבג את הקוד באמצעות הוספת echo כדי לקבל תשובה לגבי התקלה ולראות מה היא בדיוק ואיך לתקן אותה. אם יש בעיות שקשורות ל-syntax אז גם כן הן יופיעו אחרי הריצה של ה-pipeline ולוגים כדי להבין מאיפה נובעת הבעיה או למשל קבצים שאפשר להוסיף שיהיה כתוב בהם את התקלות אם ה-pipeline לא מצליח לרוץ טוב.

משימת בונוס:
נתקין helm ונוודא שהוא פועל

<img width="113" alt="Screenshot 2024-06-29 at 21 09 36" src="https://github.com/darkt2003/jar-project/assets/162579939/75ca1195-1b83-4e71-893f-4ec3c5d499df">
עריכה של הקובץ values.yaml כדי שיקח את האימג׳ מהרפוזיטורי
<img width="456" alt="Screenshot 2024-06-29 at 21 10 40" src="https://github.com/darkt2003/jar-project/assets/162579939/3c56c54a-28b1-49b2-9975-318c5a468b08">

<img width="381" alt="Screenshot 2024-06-29 at 21 13 50" src="https://github.com/darkt2003/jar-project/assets/162579939/1d1ff4cc-c90e-4896-a84c-d59908f5aa86">


יצירה של deployment ובדיקה שהוא רץ:

<img width="938" alt="Screenshot 2024-06-29 at 21 12 52" src="https://github.com/darkt2003/jar-project/assets/162579939/61ef30f3-c4b7-4bc0-a3ab-5639112b2039">









