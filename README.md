# Task 1: Data Cleaning & Preprocessing

### Dataset
- Medical Appointment No Shows (Kaggle)

### Cleaning Steps Performed
1. Standardized column names → lowercase, snake_case.
2. Fixed typo: `handcap` → `handicap`.
3. Converted `patientid` to string (identifier).
4. Converted `scheduledday` and `appointmentday` to datetime format.
5. Removed invalid ages (<0 or >120).
6. Standardized categorical columns:
   - `gender`: converted to "Male" / "Female".
   - `no-show`: converted to "Yes" / "No".
7. Removed duplicates.
8. Saved the final cleaned dataset as `cleaned_medical_appointments.csv`.

### Final Output
- Rows: ~110,526
- Columns: 14
- File: `cleaned_medical_appointments.csv`
