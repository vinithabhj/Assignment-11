# stocks-project
This is a repo for TS GenAI

## Steps to Follow

1. Add your OpenAI key to your repository Secrets. 
   
   Go to Settings -> Secrets and Variables -> Codespaces -> New repository secret -> Give Name(eg. OPENAI_API_KEY) and paste Secret Value

2. Start a Codespace by going to `Code` dropdown > Select `Codespaces` tab > Click on `Create codespace on main`

3. Create and Activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate
   ```

4. Install requirement:
   ```
   pip install -r requirements/requirements.txt
   ```

5. Read data from pickle files and create a database:
   ```
   python main.py
   ```

6. Start application:
   ```
   chainlit run app.py
   ```

7. Once the application is running, access it in browser

8. Stop the application by pressing `Ctrl + C`

9. Delete the Codespace by going to `Code` dropdown > Select `Codespaces` tab > Click on 3 dots (...) showing against your codespace and select `Delete`

10. https://github.com/vinithabhj/Assignment-11/blob/13610f6aa3c5a4ee196b40721f52a6804fcb720e/Screenshot%20(281).png

11. https://github.com/vinithabhj/Assignment-11/blob/13610f6aa3c5a4ee196b40721f52a6804fcb720e/Screenshot%20(284).png

12. https://github.com/vinithabhj/Assignment-11/blob/13610f6aa3c5a4ee196b40721f52a6804fcb720e/Screenshot%20(283).png
    
