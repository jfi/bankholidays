Simple gem to parse UK bank holidays from https://www.gov.uk/bank-holidays/.

#### Usage

Loop through all bank holidays:

    BankHolidays.all.each do |h|
      puts h[:date] # => 2012-12-25
      puts h[:name] # => Christmas day
    end

Find the next bank holiday:

    BankHolidays.next
    
#### Dependencies

Requires the **httparty** and **icalendar** gems.