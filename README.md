## Next.js App Router Course - Starter

### Start from Chapter 12: Mutating Data

- Chapter 7 - learned about SQL fetching in the /app/lib/data.ts file there are sample queries to the DB, don't need an API for this

- Chapter 8 - learned about static and dynamic rendering, usung noStore to prevent caching, this allows for dynamic rendering of pages (real-time data)

- Chapter 9 - learned about streaming, using <Suspense /> and skeletons for loading, move all fetcing to components that need them

- Chapter 11:
  1. useSearchParams - allows you to access the oarameters of the current URL. For example, this URL /dashboard/invoices?page=1&query=pending would look like this: {page: '1', query: 'pending'}
  2. usePathname - lets you read the current URL pathname. For example route `/dashboard/invoices` would return `/dashboard/invoices`.
  3. useRouter - enables navigation between routes within the client componens
  4. useDebounce - is a programming practice that limits the rate at which a function can fire. In this case, every 300 milliseconds, the search query will be updated.
