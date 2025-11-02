# 🚀 The Ultimate Guide to Full-Stack Development with Claude Code

> Build production-ready web applications in hours, not weeks. This comprehensive guide covers everything from MVP development to enterprise-grade architecture using the Charles NPM repository for Claude Code Templates.

## 📚 Table of Contents

### 🎯 [Getting Started](#-getting-started)
- [Quick Start](#quick-start-4-commands)
- [Prerequisites](#prerequisites)
- [Understanding the Architecture](#understanding-the-architecture)

### 🛠️ [Core Development Workflow](#️-core-development-workflow)
- [Step 1: Project Setup](#step-1-project-setup)
- [Step 2: Essential Tools](#step-2-essential-tools)
- [Step 3: Feature Development](#step-3-feature-development)
- [Step 4: Testing & Quality](#step-4-testing--quality)
- [Step 5: Deployment](#step-5-deployment)

### 🚀 [Advanced Development](#-advanced-development)
- [Complete Project Setup Guide](#complete-project-setup-guide)
- [Test-Driven Development](#test-driven-development)
- [Browser Automation Testing](#browser-automation-testing)
- [Database Integration](#database-integration)
- [Performance Optimization](#performance-optimization)

### 🏗️ [Architecture Deep Dive](#️-architecture-deep-dive)
- [Frontend Architecture](#frontend-architecture)
- [Backend Architecture](#backend-architecture)
- [Full-Stack JavaScript](#full-stack-javascript-good-or-not)
- [Alternative Tech Stacks](#alternative-tech-stacks)

### 💼 [Real-World Examples](#-real-world-examples)
- [Blog Platform](#blog-platform)
- [E-commerce Store](#e-commerce-store)
- [SaaS Dashboard](#saas-dashboard)
- [Portfolio Website](#portfolio-website)
- [Task Management App](#task-management-app)

### 📖 [Learning Resources](#-learning-resources)
- [Documentation](#documentation)
- [Community](#community)
- [Troubleshooting](#troubleshooting)

---

## 🎯 Getting Started

### Quick Start (4 Commands)

```bash
# 1. Create your application
/nextjs-scaffold my-app --typescript --tailwind --app-router

# 2. Install AI development assistants from Charles repository
npx @charles/claude-code-templates@latest --agent fullstack-developer
npx @charles/claude-code-templates@latest --agent backend-architect

# 3. Install testing and automation tools
npx @charles/claude-code-templates@latest --mcp playwright-mcp
npx @charles/claude-code-templates@latest --mcp neon

# 4. Start development with TDD
cd my-app
npm install --save-dev @testing-library/react @testing-library/jest-dom
npm run test:watch & npm run dev
```

**🎉 That's it! You now have a complete development environment with:**
- ✅ Modern Next.js application with TypeScript
- ✅ AI-powered development assistants
- ✅ Automated testing framework
- ✅ Database integration ready
- ✅ Browser automation testing

### Prerequisites

**Required Software:**
```bash
# Verify Node.js 18+ is installed
node --version  # Should show v18.0.0 or higher
npm --version   # Should show 9.0.0 or higher
```

**Don't have Node.js?** Download from [nodejs.org](https://nodejs.org/)

### Understanding the Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    Claude Code Ecosystem                    │
├─────────────────────────────────────────────────────────────┤
│  🤖 AI Agents          │  ⚡ Commands    │  🔌 MCPs        │
│  ┌─────────────────┐   │  ┌───────────┐  │  ┌─────────────┐ │
│  │ Fullstack Dev   │   │  │ Scaffold  │  │  │ Playwright  │ │
│  │ Backend Architect│   │  │ Testing   │  │  │ Neon DB     │ │
│  │ DB Architect    │   │  │ Deploy    │  │  │ PostgreSQL  │ │
│  │ Frontend Dev    │   │  │ Security  │  │  │ Browser     │ │
│  └─────────────────┘   │  └───────────┘  │  └─────────────┘ │
├─────────────────────────────────────────────────────────────┤
│                    Your Application                         │
│  ┌─────────────────┐   ┌─────────────────┐                 │
│  │   Frontend      │   │    Backend      │                 │
│  │   Next.js       │◄──►│   API Routes    │                 │
│  │   React         │   │   PostgreSQL    │                 │
│  │   TypeScript    │   │   Auth & Sec    │                 │
│  └─────────────────┘   └─────────────────┘                 │
└─────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Core Development Workflow

### Step 1: Project Setup

#### Automated Setup (Recommended)
```bash
# Create a new project with optimal configuration
/nextjs-scaffold my-awesome-app --typescript --tailwind --app-router

# Navigate to your project
cd my-awesome-app
```

#### Manual Setup (Alternative)
```bash
# Create Next.js app manually
npx create-next-app@latest my-awesome-app --typescript --tailwind --eslint

# Navigate to project
cd my-awesome-app

# Install Claude Code Templates from Charles repository
npx @charles/claude-code-templates@latest --agent fullstack-developer
```

**What you get:**
- 🏗️ Modern Next.js 14+ with App Router
- 🔧 TypeScript configuration
- 🎨 Tailwind CSS for styling
- ✅ ESLint and Prettier pre-configured
- 🔒 Security headers built-in
- 📱 Responsive design ready

### Step 2: Essential Tools

#### Install AI Development Team
```bash
# Core development agents from Charles repository
npx @charles/claude-code-templates@latest --agent fullstack-developer
npx @charles/claude-code-templates@latest --agent backend-architect
npx @charles/claude-code-templates@latest --agent database-architect

# Browser automation for testing
npx @charles/claude-code-templates@latest --mcp playwright-mcp

# Database integration
npx @charles/claude-code-templates@latest --mcp neon
npx @charles/claude-code-templates@latest --mcp postgresql-integration
```

#### Setup Testing Environment
```bash
# Install testing dependencies
npm install --save-dev @testing-library/react @testing-library/jest-dom jest-environment-jsdom

# Start TDD environment
npm run test:watch
```

### Step 3: Feature Development

#### TDD Development Cycle
```bash
# 1. Write tests first (Red phase)
"Create tests for user registration feature with validation"

# 2. Run failing tests (expected - Red)
npm run test:watch  # Tests fail because functionality doesn't exist yet

# 3. Implement minimal code (Green phase)
"Implement user registration to make tests pass"

# 4. Refactor and improve (Refactor phase)
"Refactor registration code while keeping tests green"

# 5. Browser testing
"Test registration flow with Playwright across different browsers"
```

#### AI-Powered Development
```bash
# Example: Add User Authentication
"Implement complete user authentication with TDD approach:
1. Write tests for registration form validation
2. Write tests for login functionality
3. Write tests for password reset
4. Implement authentication components with TypeScript
5. Create API endpoints with proper error handling
6. Add JWT token management
7. Test with Playwright for cross-browser compatibility
8. Verify accessibility compliance"
```

### Step 4: Testing & Quality

#### Testing Pyramid
```
                E2E Tests (Browser MCP)
                    Few, Comprehensive
                        │
                Integration Tests
                    Moderate Number
                        │
                Unit Tests (TDD)
                    Many, Fast
```

#### Quality Checklist
- [ ] **Unit Tests**: 80%+ coverage with Jest
- [ ] **Integration Tests**: API endpoint testing
- [ ] **E2E Tests**: Cross-browser Playwright testing
- [ ] **Accessibility**: WCAG 2.1 AA compliance
- [ ] **Performance**: Core Web Vitals达标
- [ ] **Security**: Input validation and sanitization
- [ ] **Type Safety**: Full TypeScript coverage

### Step 5: Deployment

#### Vercel Deployment (Recommended)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy to production
vercel --prod

# Set environment variables
vercel env add DATABASE_URL
vercel env add JWT_SECRET
```

#### Automated Deployment Setup
```bash
# Configure CI/CD pipeline
/setup-ci-cd-pipeline

# Optimize for production
npx @charles/claude-code-templates@latest --command vercel-deploy-optimize

# Sync environment variables
npx @charles/claude-code-templates@latest --command vercel-env-sync
```

---

## 🚀 Advanced Development

### Complete Project Setup Guide

#### Enterprise-Grade Project Structure
```
my-enterprise-app/
├── app/                           # Next.js App Router
│   ├── (auth)/                   # Authentication routes
│   │   ├── login/
│   │   ├── register/
│   │   └── reset-password/
│   ├── (dashboard)/              # Protected dashboard routes
│   │   ├── overview/
│   │   ├── analytics/
│   │   └── settings/
│   ├── api/                      # Backend API routes
│   │   ├── auth/
│   │   │   ├── register/
│   │   │   ├── login/
│   │   │   └── refresh/
│   │   ├── users/
│   │   ├── projects/
│   │   └── webhooks/
│   ├── globals.css
│   ├── layout.tsx               # Root layout
│   ├── page.tsx                 # Homepage
│   └── loading.tsx              # Loading states
├── components/                   # Reusable components
│   ├── ui/                      # Base UI components
│   │   ├── Button.tsx
│   │   ├── Input.tsx
│   │   ├── Modal.tsx
│   │   └── Table.tsx
│   ├── forms/                   # Form components
│   ├── charts/                  # Data visualization
│   └── layout/                  # Layout components
├── lib/                         # Utilities and configurations
│   ├── db.ts                    # Database connection
│   ├── auth.ts                  # Authentication logic
│   ├── utils.ts                 # Helper functions
│   ├── validations.ts           # Form validations
│   └── types.ts                 # TypeScript definitions
├── __tests__/                    # Test files
│   ├── unit/                    # Unit tests
│   ├── integration/             # Integration tests
│   └── e2e/                     # End-to-end tests
├── prisma/                      # Database schema and migrations
│   ├── schema.prisma
│   ├── migrations/
│   └── seed.ts
├── public/                      # Static assets
├── docs/                        # Documentation
├── .env.local                   # Environment variables
├── .env.example                 # Environment template
├── next.config.js               # Next.js configuration
├── tailwind.config.js           # Tailwind configuration
├── jest.config.js               # Jest testing configuration
├── playwright.config.ts         # Playwright configuration
└── README.md                    # Project documentation
```

#### Step-by-Step Implementation

**Step 1: Database Design**
```bash
# Use database architect for schema design
"Design comprehensive database schema for task management system:
1. Users table with authentication fields
2. Projects table with team collaboration
3. Tasks table with status tracking
4. Comments table for task discussions
5. Audit logs for compliance
6. Proper indexes for performance
7. Foreign key constraints for data integrity"
```

**Step 2: API Architecture**
```bash
# Design RESTful API with backend architect
"Create complete API architecture:
1. Authentication endpoints (register, login, logout, refresh)
2. User management (CRUD operations, profile management)
3. Project management (team collaboration, permissions)
4. Task management (CRUD, filtering, search, pagination)
5. Real-time updates (WebSocket integration)
6. Webhook handling for external integrations
7. Rate limiting and security middleware
8. API versioning strategy (/v1/, /v2/)"
```

**Step 3: Frontend Development**
```bash
# Build frontend with fullstack developer
"Create modern frontend with:
1. Authentication flow (login, register, password reset)
2. Dashboard with analytics and metrics
3. Project management interface with drag-and-drop
4. Task management with real-time updates
5. Team collaboration features
6. Responsive design for all devices
7. Accessibility compliance (WCAG 2.1 AA)
8. Progressive Web App features"
```

### Test-Driven Development

#### TDD Workflow Example

**1. Write the Test First (Red)**
```typescript
// __tests__/features/user-registration.test.ts
import { render, screen, fireEvent, waitFor } from '@testing-library/react'
import { RegisterForm } from '@/components/auth/RegisterForm'

describe('User Registration', () => {
  it('should validate email format', async () => {
    render(<RegisterForm />)

    const emailInput = screen.getByLabelText('Email')
    const submitButton = screen.getByRole('button', { name: 'Register' })

    // Enter invalid email
    fireEvent.change(emailInput, { target: { value: 'invalid-email' } })
    fireEvent.click(submitButton)

    await waitFor(() => {
      expect(screen.getByText('Please enter a valid email')).toBeInTheDocument()
    })
  })

  it('should register user with valid data', async () => {
    render(<RegisterForm />)

    // Fill form with valid data
    fireEvent.change(screen.getByLabelText('Email'), { target: { value: 'user@example.com' } })
    fireEvent.change(screen.getByLabelText('Password'), { target: { value: 'SecurePass123!' } })
    fireEvent.change(screen.getByLabelText('Name'), { target: { value: 'John Doe' } })

    fireEvent.click(screen.getByRole('button', { name: 'Register' }))

    await waitFor(() => {
      expect(screen.getByText('Registration successful!')).toBeInTheDocument()
    })
  })
})
```

**2. Run Failing Test (Expected Red)**
```bash
npm run test:watch
# Test fails because RegisterForm component doesn't exist yet
```

**3. Implement Minimal Code (Green)**
```typescript
// components/auth/RegisterForm.tsx
'use client'

import { useState } from 'react'
import { useForm } from 'react-hook-form'
import { zodResolver } from '@hookform/resolvers/zod'
import { z } from 'zod'

const registerSchema = z.object({
  email: z.string().email('Please enter a valid email'),
  password: z.string().min(8, 'Password must be at least 8 characters'),
  name: z.string().min(2, 'Name must be at least 2 characters')
})

type RegisterForm = z.infer<typeof registerSchema>

export function RegisterForm() {
  const [isLoading, setIsLoading] = useState(false)
  const [message, setMessage] = useState('')

  const {
    register,
    handleSubmit,
    formState: { errors }
  } = useForm<RegisterForm>({
    resolver: zodResolver(registerSchema)
  })

  const onSubmit = async (data: RegisterForm) => {
    setIsLoading(true)
    try {
      const response = await fetch('/api/auth/register', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(data)
      })

      if (response.ok) {
        setMessage('Registration successful!')
      }
    } catch (error) {
      setMessage('Registration failed. Please try again.')
    } finally {
      setIsLoading(false)
    }
  }

  return (
    <form onSubmit={handleSubmit(onSubmit)} className="space-y-4">
      <div>
        <label htmlFor="name">Name</label>
        <input {...register('name')} />
        {errors.name && <span>{errors.name.message}</span>}
      </div>

      <div>
        <label htmlFor="email">Email</label>
        <input {...register('email')} />
        {errors.email && <span>{errors.email.message}</span>}
      </div>

      <div>
        <label htmlFor="password">Password</label>
        <input type="password" {...register('password')} />
        {errors.password && <span>{errors.password.message}</span>}
      </div>

      <button type="submit" disabled={isLoading}>
        {isLoading ? 'Registering...' : 'Register'}
      </button>

      {message && <p>{message}</p>}
    </form>
  )
}
```

**4. Refactor and Improve (Refactor)**
- Extract reusable components
- Improve error handling
- Add loading states
- Enhance accessibility

### Browser Automation Testing

#### Playwright MCP Integration
```bash
# Install Playwright MCP from Charles repository
npx @charles/claude-code-templates@latest --mcp playwright-mcp

# Request comprehensive browser testing
"Run complete E2E test suite with Playwright:
1. Test user registration flow across Chrome, Firefox, Safari
2. Verify responsive design on mobile and tablet
3. Test accessibility with keyboard navigation
4. Validate form submissions and error handling
5. Test real-time collaboration features
6. Verify performance under load
7. Test offline functionality
8. Validate SEO and meta tags"
```

#### Test Scenarios
```typescript
// e2e/user-workflows.spec.ts
import { test, expect } from '@playwright/test'

test.describe('User Workflows', () => {
  test.beforeEach(async ({ page }) => {
    await page.goto('/')
  })

  test('complete user registration and login flow', async ({ page }) => {
    // Registration
    await page.click('[data-testid="register-button"]')
    await page.fill('[data-testid="email-input"]', 'test@example.com')
    await page.fill('[data-testid="password-input"]', 'SecurePass123!')
    await page.fill('[data-testid="name-input"]', 'Test User')
    await page.click('[data-testid="submit-button"]')

    // Verify registration success
    await expect(page.locator('[data-testid="success-message"]')).toBeVisible()

    // Login
    await page.goto('/login')
    await page.fill('[data-testid="email-input"]', 'test@example.com')
    await page.fill('[data-testid="password-input"]', 'SecurePass123!')
    await page.click('[data-testid="login-button"]')

    // Verify dashboard access
    await expect(page).toHaveURL('/dashboard')
    await expect(page.locator('[data-testid="welcome-message"]')).toContainText('Test User')
  })

  test('task management workflow', async ({ page }) => {
    // Login first
    await loginAsTestUser(page)

    // Create new task
    await page.click('[data-testid="new-task-button"]')
    await page.fill('[data-testid="task-title"]', 'Test Task')
    await page.fill('[data-testid="task-description"]', 'This is a test task')
    await page.click('[data-testid="save-task"]')

    // Verify task appears in list
    await expect(page.locator('[data-testid="task-list"]')).toContainText('Test Task')

    // Mark task as complete
    await page.click('[data-testid="task-checkbox"]')
    await expect(page.locator('[data-testid="task-status"]')).toContainText('Completed')
  })
})

async function loginAsTestUser(page: Page) {
  await page.goto('/login')
  await page.fill('[data-testid="email-input"]', 'test@example.com')
  await page.fill('[data-testid="password-input"]', 'SecurePass123!')
  await page.click('[data-testid="login-button"]')
  await expect(page).toHaveURL('/dashboard')
}
```

### Database Integration

#### Neon PostgreSQL Setup
```bash
# Install Neon integration from Charles repository
npx @charles/claude-code-templates@latest --mcp neon

# Request database setup
"Set up Neon PostgreSQL database with:
1. Create database cluster
2. Configure connection pooling
3. Set up database schema with migrations
4. Create seed data for development
5. Configure backup strategy
6. Set up read replicas for performance
7. Implement connection monitoring
8. Add health check endpoints"
```

#### Database Schema Example
```prisma
// prisma/schema.prisma
generator client {
  provider = "prisma-client-js"
}

datasource db {
  provider = "postgresql"
  url      = env("DATABASE_URL")
}

model User {
  id        String   @id @default(cuid())
  email     String   @unique
  name      String
  password  String
  avatar    String?
  role      Role     @default(USER)
  createdAt DateTime @default(now())
  updatedAt DateTime @updatedAt

  projects    Project[]
  tasks       Task[]
  sessions    Session[]

  @@map("users")
}

model Project {
  id          String   @id @default(cuid())
  name        String
  description String?
  color       String   @default("#3B82F6")
  ownerId     String
  createdAt   DateTime @default(now())
  updatedAt   DateTime @updatedAt

  owner   User    @relation(fields: [ownerId], references: [id], onDelete: Cascade)
  tasks   Task[]
  members ProjectMember[]

  @@map("projects")
}

model Task {
  id          String     @id @default(cuid())
  title       String
  description String?
  status      TaskStatus @default(TODO)
  priority    Priority   @default(MEDIUM)
  dueDate     DateTime?
  projectId   String
  assigneeId  String?
  createdAt   DateTime   @default(now())
  updatedAt   DateTime   @updatedAt

  project  Project  @relation(fields: [projectId], references: [id], onDelete: Cascade)
  assignee User?    @relation(fields: [assigneeId], references: [id])

  @@map("tasks")
}

enum Role {
  USER
  ADMIN
}

enum TaskStatus {
  TODO
  IN_PROGRESS
  REVIEW
  COMPLETED
}

enum Priority {
  LOW
  MEDIUM
  HIGH
  URGENT
}
```

### Performance Optimization

#### Bundle Optimization
```bash
# Install bundle analyzer
npm install --save-dev @next/bundle-analyzer

# Configure next.config.js
const withBundleAnalyzer = require('@next/bundle-analyzer')({
  enabled: process.env.ANALYZE === 'true',
})

/** @type {import('next').NextConfig} */
const nextConfig = {
  experimental: {
    optimizePackageImports: ['lucide-react', '@heroicons/react'],
  },
  images: {
    formats: ['image/webp', 'image/avif'],
    deviceSizes: [640, 750, 828, 1080, 1200, 1920, 2048, 3840],
  },
  compiler: {
    removeConsole: process.env.NODE_ENV === 'production',
  },
}

module.exports = withBundleAnalyzer(nextConfig)
```

#### Caching Strategy
```typescript
// lib/cache.ts
import { LRUCache } from 'lru-cache'

export const cache = new LRUCache<string, any>({
  max: 500, // Maximum number of items
  ttl: 1000 * 60 * 5, // 5 minutes
})

export async function getCachedData<T>(
  key: string,
  fetcher: () => Promise<T>
): Promise<T> {
  const cached = cache.get(key)
  if (cached) return cached

  const data = await fetcher()
  cache.set(key, data)
  return data
}

// Usage example
export async function getProjects(userId: string) {
  return getCachedData(
    `projects:${userId}`,
    () => prisma.project.findMany({ where: { ownerId: userId } })
  )
}
```

---

## 🏗️ Architecture Deep Dive

### Frontend Architecture

#### Component Architecture
```
components/
├── ui/                    # Atomic Design System
│   ├── atoms/            # Basic elements (Button, Input)
│   ├── molecules/        # Simple combinations (SearchBox)
│   ├── organisms/        # Complex sections (Header)
│   └── templates/        # Page layouts
├── features/             # Feature-specific components
│   ├── auth/
│   ├── projects/
│   └── tasks/
└── layouts/              # Layout components
    ├── DashboardLayout.tsx
    └── AuthLayout.tsx
```

#### State Management Strategy
```typescript
// lib/state-management.ts
import { create } from 'zustand'
import { devtools, persist } from 'zustand/middleware'

// Global app state
interface AppState {
  user: User | null
  theme: 'light' | 'dark'
  sidebarOpen: boolean
  setUser: (user: User | null) => void
  toggleTheme: () => void
  toggleSidebar: () => void
}

export const useAppStore = create<AppState>()(
  devtools(
    persist(
      (set) => ({
        user: null,
        theme: 'light',
        sidebarOpen: true,
        setUser: (user) => set({ user }),
        toggleTheme: () => set((state) => ({ theme: state.theme === 'light' ? 'dark' : 'light' })),
        toggleSidebar: () => set((state) => ({ sidebarOpen: !state.sidebarOpen })),
      }),
      { name: 'app-store' }
    )
  )
)

// Server state management with React Query
import { QueryClient, QueryClientProvider } from '@tanstack/react-query'

const queryClient = new QueryClient({
  defaultOptions: {
    queries: {
      staleTime: 1000 * 60 * 5, // 5 minutes
      cacheTime: 1000 * 60 * 10, // 10 minutes
    },
  },
})
```

### Backend Architecture

#### API Design Patterns
```typescript
// lib/api-handler.ts
import { NextRequest, NextResponse } from 'next/server'
import { z } from 'zod'
import { fromZodError } from 'zod-validation-error'

export function withValidation<T>(
  schema: z.ZodSchema<T>,
  handler: (data: T, req: NextRequest) => Promise<NextResponse>
) {
  return async (req: NextRequest) => {
    try {
      const body = await req.json()
      const data = schema.parse(body)
      return await handler(data, req)
    } catch (error) {
      if (error instanceof z.ZodError) {
        return NextResponse.json(
          { error: fromZodError(error).message },
          { status: 400 }
        )
      }
      return NextResponse.json(
        { error: 'Internal server error' },
        { status: 500 }
      )
    }
  }
}

// Usage example
const createTaskSchema = z.object({
  title: z.string().min(1).max(200),
  description: z.string().optional(),
  projectId: z.string().cuid(),
  priority: z.enum(['LOW', 'MEDIUM', 'HIGH', 'URGENT']).optional(),
})

export const POST = withValidation(createTaskSchema, async (data, req) => {
  const task = await prisma.task.create({
    data: {
      ...data,
      assigneeId: req.user.id,
    },
  })

  return NextResponse.json(task, { status: 201 })
})
```

#### Authentication & Authorization
```typescript
// lib/auth.ts
import jwt from 'jsonwebtoken'
import bcrypt from 'bcryptjs'
import { NextRequest } from 'next/server'

const JWT_SECRET = process.env.JWT_SECRET!

export async function hashPassword(password: string): Promise<string> {
  return bcrypt.hash(password, 12)
}

export async function verifyPassword(password: string, hash: string): Promise<boolean> {
  return bcrypt.compare(password, hash)
}

export function generateToken(payload: any): string {
  return jwt.sign(payload, JWT_SECRET, { expiresIn: '7d' })
}

export function verifyToken(token: string): any {
  return jwt.verify(token, JWT_SECRET)
}

export async function authenticate(req: NextRequest): Promise<User | null> {
  const token = req.headers.get('authorization')?.replace('Bearer ', '')

  if (!token) return null

  try {
    const payload = verifyToken(token)
    return await prisma.user.findUnique({ where: { id: payload.userId } })
  } catch {
    return null
  }
}

export function authorize(roles: Role[]) {
  return (handler: (req: NextRequest, user: User) => Promise<NextResponse>) => {
    return async (req: NextRequest) => {
      const user = await authenticate(req)

      if (!user || !roles.includes(user.role)) {
        return NextResponse.json(
          { error: 'Unauthorized' },
          { status: 401 }
        )
      }

      return handler(req, user)
    }
  }
}
```

### Full-Stack JavaScript: Good or Not?

This is a crucial architectural decision that deserves careful consideration.

#### ✅ Advantages of Full-Stack JavaScript

**1. Development Efficiency**
- **Unified Language**: Team masters JavaScript/TypeScript for both frontend and backend
- **Code Sharing**: Types, validation logic, utilities can be shared across the stack
- **Rapid Prototyping**: MVP development time reduced by 60-80%
- **Full-Stack Developers**: One developer can handle entire features

**2. Ecosystem Maturity**
- **NPM Universe**: Largest package registry with 2M+ packages
- **Modern Frameworks**: Next.js, Express, Fastify, Prisma are production-ready
- **Tooling**: Unified development, testing, and build toolchain
- **Community**: Huge talent pool and extensive learning resources

**3. Business Benefits**
- **Faster Time to Market**: Critical for startups and competitive markets
- **Lower Development Costs**: Fewer specialized skills needed
- **Easier Maintenance**: Consistent codebase across the stack
- **Better Team Collaboration**: Frontend and backend can understand each other's code

#### ⚠️ Potential Limitations

**1. Performance Considerations**
```javascript
// JavaScript (Node.js) - Single-threaded event loop
app.post('/api/heavy-computation', (req, res) => {
  // CPU-intensive tasks can block the event loop
  const result = heavyDataProcessing(req.data) // ⚠️ Blocking
  res.json(result)
})

// Go - Goroutines for concurrent processing
func heavyComputationHandler(w http.ResponseWriter, r *http.Request) {
    go func() {
        result := heavyDataProcessing(data) // ✅ Non-blocking
        w.Write(result)
    }()
}
```

**2. Enterprise Requirements**
- **Regulatory Compliance**: Financial/healthcare industries prefer established languages
- **Legacy Integration**: Enterprise systems often built on Java/.NET ecosystems
- **Performance Guarantees**: Mission-critical systems may require compiled languages

#### 🎯 When to Choose Full-Stack JavaScript

**Perfect For:**
- ✅ **Startups & MVPs**: Speed to market is crucial
- ✅ **Web Applications**: CRUD-heavy business applications
- ✅ **API Services**: RESTful APIs and GraphQL endpoints
- ✅ **Internal Tools**: Dashboards, admin panels, internal software
- ✅ **Digital Agencies**: Fast project delivery for clients
- ✅ **Small to Medium Teams**: Limited specialized resources

**Consider Alternatives For:**
- ⚠️ **High-Frequency Trading**: Microsecond latency requirements
- ⚠️ **Video Processing**: CPU-intensive media workloads
- ⚠️ **Enterprise Banking**: Strict compliance and audit requirements
- ⚠️ **Game Servers**: Real-time multiplayer with thousands of concurrent users
- ⚠️ **ML/AI Pipelines**: Heavy computational requirements

#### 📈 Performance Comparison

```javascript
// Node.js Request Handling
const express = require('express')
const app = express()

app.get('/api/data', async (req, res) => {
  // ~10,000-50,000 requests/second
  const data = await database.query('SELECT * FROM table')
  res.json(data)
})

// Go Request Handling
package main

import "net/http"
import "database/sql"

func handler(w http.ResponseWriter, r *http.Request) {
  // ~100,000-500,000 requests/second
  data, _ := db.Query("SELECT * FROM table")
  json.NewEncoder(w).Encode(data)
}

// Rust Request Handling
use actix_web::{get, web, App, HttpServer, Responder};

#[get("/api/data")]
async fn get_data() -> impl Responder {
  // ~500,000-1,000,000+ requests/second
  let data = db.query("SELECT * FROM table").await;
  web::Json(data)
}
```

#### 💡 My Recommendation

**For 95% of web applications, full-stack TypeScript is the optimal choice** because:

1. **Development Speed**: 3-5x faster development with AI assistance
2. **TypeScript Benefits**: Compile-time type safety prevents runtime errors
3. **Ecosystem Maturity**: Battle-tested libraries and frameworks
4. **Deployment Simplicity**: Vercel, Netlify, Railway offer one-click deployment
5. **Future-Proof**: Easy to migrate performance-critical components later

**Hybrid Approach for Performance-Critical Apps:**
```
Frontend: Next.js + TypeScript
      │
      ├─ API Layer: Node.js/Express (Most APIs)
      │
      ├─ Heavy Processing: Go/Rust microservices
      │
      └─ Database: PostgreSQL + Redis
```

### Alternative Tech Stacks

#### Next.js + Go for High Performance
```go
// main.go
package main

import (
    "github.com/gin-gonic/gin"
    "gorm.io/gorm"
)

type Task struct {
    ID    string `json:"id" gorm:"primaryKey"`
    Title string `json:"title"`
    Done  bool   `json:"done"`
}

func main() {
    r := gin.Default()

    // API routes
    r.GET("/api/tasks", getTasks)
    r.POST("/api/tasks", createTask)
    r.PUT("/api/tasks/:id", updateTask)
    r.DELETE("/api/tasks/:id", deleteTask)

    r.Run(":8080")
}

func getTasks(c *gin.Context) {
    var tasks []Task
    db.Find(&tasks)
    c.JSON(200, tasks)
}
```

#### Next.js + Python/FastAPI for Data Science
```python
# main.py
from fastapi import FastAPI, Depends
from pydantic import BaseModel
from sqlalchemy.orm import Session

app = FastAPI()

class Task(BaseModel):
    id: str
    title: str
    done: bool = False
    priority: str = "medium"

class Database:
    def __init__(self):
        # Database connection
        pass

# Dependency injection
def get_db():
    db = Database()
    try:
        yield db
    finally:
        db.close()

@app.get("/api/tasks")
async def get_tasks(db: Session = Depends(get_db)):
    tasks = db.query(Task).all()
    return tasks

@app.post("/api/tasks")
async def create_task(task: Task, db: Session = Depends(get_db)):
    db.add(task)
    db.commit()
    db.refresh(task)
    return task
```

#### Next.js + Rust for Maximum Performance
```rust
// main.rs
use serde::{Deserialize, Serialize};
use warp::Filter;

#[derive(Serialize, Deserialize)]
struct Task {
    id: String,
    title: String,
    done: bool,
}

#[tokio::main]
async fn main() {
    // CORS for frontend
    let cors = warp::cors()
        .allow_any_origin()
        .allow_headers(vec!["content-type"])
        .allow_methods(vec!["GET", "POST", "PUT", "DELETE"]);

    // GET /api/tasks
    let get_tasks = warp::path("api")
        .and(warp::path("tasks"))
        .and(warp::get())
        .and_then(|| async move {
            // Fetch tasks from database
            let tasks = vec![
                Task { id: "1".to_string(), title: "Task 1".to_string(), done: false },
                Task { id: "2".to_string(), title: "Task 2".to_string(), done: true },
            ];
            Ok::<_, warp::Rejection>(warp::reply::json(&tasks))
        });

    let routes = get_tasks.with(cors);

    println!("Server running on http://localhost:3030");
    warp::serve(routes).run(([127, 0, 0, 1], 3030)).await;
}
```

---

## 💼 Real-World Examples

### Blog Platform

**Features:**
- User authentication and profiles
- Rich text editor with Markdown support
- Categories, tags, and search functionality
- Comments system with moderation
- SEO optimization and social sharing
- Analytics dashboard for authors

**Technical Stack:**
```bash
# Project setup
/nextjs-scaffold tech-blog --typescript --tailwind

# AI assistants from Charles repository
npx @charles/claude-code-templates@latest --agent fullstack-developer
npx @charles/claude-code-templates@latest --agent backend-architect

# Testing
npx @charles/claude-code-templates@latest --mcp playwright-mcp

# Database
npx @charles/claude-code-templates@latest --mcp neon
```

**Key Implementation:**
```typescript
// Blog post creation with TDD
describe('Blog Post Creation', () => {
  it('should create blog post with valid data', async () => {
    const result = await createBlogPost({
      title: 'My First Post',
      content: 'This is my blog content...',
      category: 'technology',
      tags: ['programming', 'webdev']
    })

    expect(result.id).toBeDefined()
    expect(result.slug).toBe('my-first-post')
  })
})
```

### E-commerce Store

**Features:**
- Product catalog with search and filtering
- Shopping cart and wishlist
- Secure payment processing (Stripe)
- Order tracking and history
- Inventory management
- Customer reviews and ratings

**Technical Stack:**
```bash
# E-commerce specific setup
/nextjs-scaffold mystore --typescript --tailwind

# Payment integration
npx @charles/claude-code-templates@latest --mcp stripe

# Database for inventory
npx @charles/claude-code-templates@latest --mcp postgresql-integration
```

**Complex Features:**
```typescript
// Shopping cart with real-time updates
interface CartItem {
  productId: string
  quantity: number
  price: number
  variant?: ProductVariant
}

interface Cart {
  items: CartItem[]
  total: number
  subtotal: number
  tax: number
  shipping: number
}

// Real-time inventory management
export async function updateInventory(productId: string, quantity: number) {
  const inventory = await prisma.inventory.findUnique({
    where: { productId }
  })

  if (inventory.stock < quantity) {
    throw new Error('Insufficient stock')
  }

  return await prisma.inventory.update({
    where: { productId },
    data: { stock: inventory.stock - quantity }
  })
}
```

### SaaS Dashboard

**Features:**
- Multi-tenant architecture
- User role management (Admin, User, Viewer)
- Real-time analytics and metrics
- Data visualization with charts
- Team collaboration tools
- Subscription and billing management

**Advanced Architecture:**
```typescript
// Multi-tenant database design
interface Tenant {
  id: string
  name: string
  domain: string
  plan: 'free' | 'pro' | 'enterprise'
  settings: TenantSettings
}

interface TenantSettings {
  branding: BrandingConfig
  features: FeatureFlags
  limits: UsageLimits
}

// Row-level security for multi-tenancy
export async function getUserProjects(userId: string, tenantId: string) {
  return await prisma.project.findMany({
    where: {
      tenantId,
      members: {
        some: { userId }
      }
    }
  })
}
```

### Portfolio Website

**Features:**
- Dynamic project showcase
- Contact form with email notifications
- Blog integration
- Skills and experience timeline
- Testimonials and client reviews
- Resume/CV download

**Focus on Performance:**
```typescript
// Optimized image loading
import Image from 'next/image'
import { getBlurDataURL } from '@/lib/images'

export function ProjectImage({ src, alt }: { src: string, alt: string }) {
  const [blurDataURL, setBlurDataURL] = useState<string>()

  useEffect(() => {
    getBlurDataURL(src).then(setBlurDataURL)
  }, [src])

  return (
    <Image
      src={src}
      alt={alt}
      placeholder="blur"
      blurDataURL={blurDataURL}
      sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
    />
  )
}
```

### Task Management App

**Features:**
- Kanban board with drag-and-drop
- Real-time collaboration
- Task assignments and deadlines
- File attachments and comments
- Time tracking and reporting
- Integration with external tools

**Real-time Features:**
```typescript
// WebSocket integration for real-time updates
import { useEffect, useState } from 'react'
import { useSocket } from '@/hooks/useSocket'

export function useRealTimeTasks(projectId: string) {
  const [tasks, setTasks] = useState<Task[]>([])
  const socket = useSocket()

  useEffect(() => {
    // Listen for real-time updates
    socket.on('task:updated', (updatedTask: Task) => {
      setTasks(prev => prev.map(task =>
        task.id === updatedTask.id ? updatedTask : task
      ))
    })

    socket.on('task:created', (newTask: Task) => {
      setTasks(prev => [...prev, newTask])
    })

    socket.on('task:deleted', (taskId: string) => {
      setTasks(prev => prev.filter(task => task.id !== taskId))
    })

    return () => {
      socket.off('task:updated')
      socket.off('task:created')
      socket.off('task:deleted')
    }
  }, [socket, projectId])

  return tasks
}
```

---

## 📖 Learning Resources

### Documentation

**Official Documentation:**
- [Next.js Documentation](https://nextjs.org/docs) - Comprehensive guide to Next.js
- [Claude Code Documentation](https://docs.claude.ai/claude-code) - AI assistant documentation
- [Vercel Deployment Guide](https://vercel.com/docs) - Platform deployment
- [TypeScript Handbook](https://www.typescriptlang.org/docs) - TypeScript learning
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Utility-first CSS

**Template System Documentation:**
- [Charles Claude Code Templates](https://aitmpl.com) - Interactive component browser
- [Component Catalog](https://aitmpl.com/components) - 600+ available templates
- [API Reference](https://aitmpl.com/docs) - Detailed API documentation
- [Best Practices Guide](https://aitmpl.com/guides) - Development guidelines

### Community

**Get Help and Connect:**
- [GitHub Repository](https://github.com/anthropics/claude-code-templates) - Source code and issues
- [Discord Community](https://discord.gg/claude) - Chat with other developers
- [Community Forum](https://github.com/anthropics/claude-code-templates/discussions) - Q&A and discussions
- [Showcase Gallery](https://aitmpl.com/showcase) - Projects built with templates

**Contributing:**
- [Contributing Guide](https://github.com/anthropics/claude-code-templates/blob/main/CONTRIBUTING.md)
- [Code of Conduct](https://github.com/anthropics/claude-code-templates/blob/main/CODE_OF_CONDUCT.md)
- [Security Policy](https://github.com/anthropics/claude-code-templates/blob/main/SECURITY.md)

### Troubleshooting

**Common Issues and Solutions:**

#### Build Errors
```bash
# Clear cache and reinstall dependencies
rm -rf node_modules .next
npm install
npm run build

# Check for TypeScript errors
npm run type-check
```

#### Port Conflicts
```bash
# Kill process on port 3000
lsof -ti:3000 | xargs kill -9

# Use different port
npm run dev -- -p 3001
```

#### Database Connection Issues
```bash
# Check database connection
npx @charles/claude-code-templates@latest --mcp neon

# Verify environment variables
echo $DATABASE_URL
```

#### Performance Issues
```bash
# Analyze bundle size
npm run build
npm run analyze

# Check for memory leaks
npm run dev:profile
```

**Getting Help:**
1. **Check Documentation**: Search [aitmpl.com/docs](https://aitmpl.com/docs)
2. **Search Issues**: Check [GitHub Issues](https://github.com/anthropics/claude-code-templates/issues)
3. **Ask Community**: Post in [Discord](https://discord.gg/claude)
4. **Contact Support**: claude-code@anthropic.com

---

## 🎉 Congratulations!

You now have everything you need to build production-ready web applications with Claude Code Templates.

### Key Takeaways

1. **Start Simple**: Begin with the quick start and iterate
2. **Use AI Assistants**: Leverage the specialized agents for complex tasks
3. **Test Everything**: Follow TDD principles for reliable code
4. **Deploy Early**: Use Vercel for one-click deployment
5. **Iterate Fast**: The template system enables rapid development

### Your Next Steps

1. **Build Your First Project**: Follow the quick start guide using the Charles repository
2. **Explore Templates**: Browse [aitmpl.com](https://aitmpl.com) for available components
3. **Join the Community**: Connect with other developers on Discord
4. **Share Your Work**: Submit your project to the showcase gallery

### Remember

- **Quality Over Speed**: Use TDD to ensure code quality
- **Security First**: Implement proper authentication and validation
- **Performance Matters**: Optimize for Core Web Vitals
- **Accessibility**: Ensure WCAG 2.1 AA compliance
- **Keep Learning**: The web development landscape evolves constantly

**Happy Building! 🚀**

If you need help at any point, remember that the AI agents are always available to assist you. Just ask them questions or request features - they're designed to make your development journey smoother and more productive.

---

**Built with ❤️ using Charles Claude Code Templates**

*For more templates, agents, and inspiration, visit: [aitmpl.com](https://aitmpl.com)*