#lang racket

(module reader racket
  (provide read-syntax)
  (define (read-syntax name port)
    ))

(define true #t)
(define false #f)
(define debug #f)

(define (promt-for-input string)
  (newline)
  (display string)
  (newline))

(define (tagged-list? exp tag)
  (if (pair? exp)
      (eq? (car exp) tag)
      false))

(define (user-initial-environment) (interecation-environment))

(define (display-line x)
  #; (newline)
  #; (display x)
   (show #t (pretty x)))

;;append-rule

(define (append x y)
  ())

(define (append-to-form x y z)
  ())

;;Query-reader

(define (query-driver-loop)
  (promt-for-input input-promt)
  (let (q (query-syntax-process (read)))