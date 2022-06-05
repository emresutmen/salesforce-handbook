# Salesforce Data Cleaning

In a Salesforce deciding what data to delete from production is a delicate decision. The choice to delete must be made based on the business requirements, data retention policies, and other critical factors. However, there are general categories of data that might be considered for deletion:

1. **Obsolete Data**: Data that's no longer relevant for your business processes.
   - Examples: Old promotional campaign records, outdated pricing data, legacy product listings.
   
2. **Duplicate Data**: Repeated records can clutter the system.
   - Examples: Multiple contact records for the same individual, duplicate accounts or opportunities.

3. **Test Data**: Data that was created for testing purposes and was not cleaned up post-testing.
   - Examples: Accounts with names like "Test Account" or "Dummy Data."

4. **Incomplete or Inaccurate Data**: Records that have missing or wrong data which can't be corrected.
   - Examples: Leads with missing contact information, accounts without addresses.

5. **Old Activity Records**: Completed tasks or events that are no longer relevant.
   - Examples: Completed tasks from several years ago, past events that aren't tied to compliance or long-term reference.

6. **Old Chatter Posts**: Conversational records that might no longer be necessary.
   - Examples: Chatter posts discussing resolved issues, outdated announcements.

7. **Archived Data**: Data that's been backed up and doesn't need to be in the active system.
   - Examples: Historical sales records, old contracts.

**Precautions**:
1. **Backup**: Always ensure you have a recent backup of any data you're planning to delete.
2. **Consultation**: Consult with stakeholders to make sure you're not deleting anything critical to a specific department or function.
3. **Data Retention Policies**: Ensure you're adhering to any legal or industry-specific data retention requirements.
4. **Phased Deletion**: Instead of deleting massive chunks of data at once, consider a phased approach to monitor any unintended consequences.
5. **Tools**: Utilize tools like Salesforce's Data Loader or native data export functions to handle data carefully.

Always approach data deletion with caution and a clear strategy. If unsure, seek guidance from a Salesforce expert or consultant.