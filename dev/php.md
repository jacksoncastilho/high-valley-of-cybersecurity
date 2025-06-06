### Debug
header('Content-Type: text/json');

set_error_handler(function() {
    print_r(func_get_args());
});

set_exception_handler(function() {
    print_r(func_get_args());
});
