def wsgi_application(environ, start_response):
  # бизнес-логика
  status = '200 OK'
  headers = [
  ('Content-Type', 'text/plain')
  ]
  body = environ['QUERY_STRING'].replase('&','\n')
  start_response(status, headers )
  return [ body ]
