<template>
  <div class="container">
    <div class="row justify-content-center" style="min-height: 100vh;">
        <div class="col-md-4">
            <div class="card mt-5">
                <div class="card-header text-center">
                    <h4>เข้าสู่ระบบ</h4>
                </div>
                <div class="card-body">
                    <form>
                        <div class="mb-3">
                            <label for="username" class="form-label">ชื่อผู้ใช้</label>
                            <input type="text" class="form-control" id="username" required>
                        </div>
                        <div class="mb-3">
                            <label for="password" class="form-label">รหัสผ่าน</label>
                            <input type="password" class="form-control" id="password" required>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">เข้าสู่ระบบ</button>
                    </form>
                </div>
                <div class="card-footer text-center">
                    <a href="#">ลืมรหัสผ่าน?</a>
                </div>
            </div>
        </div>
    </div>
</div>
</template>
