module Jekyll
  class ShellCommandGenerator < Generator
    safe true
    priority :high

    def generate(site)
      # Thực thi lệnh shell
      result = `ls -la`  # Ví dụ: danh sách file
      # Gán kết quả vào biến custom trong site
      site.config['shell_output'] = result
    end
  end
end
