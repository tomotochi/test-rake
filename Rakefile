require "net/http"

task :default => "test"

task "test" do
  Net::HTTP.start("www.google.co.jp", 80) do |http|
    response = http.head("/index.html")
    p response
  end
end
