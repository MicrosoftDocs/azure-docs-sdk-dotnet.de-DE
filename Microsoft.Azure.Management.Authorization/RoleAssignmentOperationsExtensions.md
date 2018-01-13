<Type Name="RoleAssignmentOperationsExtensions" FullName="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RoleAssignmentOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RoleAssignmentOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RoleAssignmentOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RoleAssignmentOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult Create (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult Create(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Create(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid, parameters As RoleAssignmentCreateParameters) As RoleAssignmentCreateResult" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Create (operations, scope, roleAssignmentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-101">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-101">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-102">Required.</span></span> <span data-ttu-id="1888f-103">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-103">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-104">Required.</span></span> <span data-ttu-id="1888f-105">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-105">Role assignment name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-106">Required.</span></span> <span data-ttu-id="1888f-107">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-107">Role assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-108">Rollenzuweisung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="1888f-108">Create role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-109">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="1888f-109">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid, parameters As RoleAssignmentCreateParameters) As Task(Of RoleAssignmentCreateResult)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateAsync (operations, scope, roleAssignmentName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-110">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-110">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-111">Required.</span></span> <span data-ttu-id="1888f-112">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-112">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-113">Required.</span></span> <span data-ttu-id="1888f-114">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-114">Role assignment name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-115">Required.</span></span> <span data-ttu-id="1888f-116">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-116">Role assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-117">Rollenzuweisung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="1888f-117">Create role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-118">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="1888f-118">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult CreateById (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult CreateById(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateById(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateById (operations As IRoleAssignmentOperations, roleAssignmentId As String, parameters As RoleAssignmentCreateParameters) As RoleAssignmentCreateResult" />
      <MemberSignature Language="F#" Value="static member CreateById : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateById (operations, roleAssignmentId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-119">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-119">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-120">Required.</span></span> <span data-ttu-id="1888f-121">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-121">Role assignment Id</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-122">Required.</span></span> <span data-ttu-id="1888f-123">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-123">Role assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-124">Erstellen Sie die rollenzuweisung nach ID auf.</span><span class="sxs-lookup"><span data-stu-id="1888f-124">Create role assignment by Id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-125">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="1888f-125">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateByIdAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateByIdAsync (operations As IRoleAssignmentOperations, roleAssignmentId As String, parameters As RoleAssignmentCreateParameters) As Task(Of RoleAssignmentCreateResult)" />
      <MemberSignature Language="F#" Value="static member CreateByIdAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.CreateByIdAsync (operations, roleAssignmentId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-126">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-126">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-127">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-127">Required.</span></span> <span data-ttu-id="1888f-128">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-128">Role assignment Id</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-129">Required.</span></span> <span data-ttu-id="1888f-130">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-130">Role assignment.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-131">Erstellen Sie die rollenzuweisung nach ID auf.</span><span class="sxs-lookup"><span data-stu-id="1888f-131">Create role assignment by Id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-132">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="1888f-132">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult Delete (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult Delete(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Delete(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid) As RoleAssignmentDeleteResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Delete (operations, scope, roleAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-133">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-133">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-134">Required.</span></span> <span data-ttu-id="1888f-135">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-135">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-136">Required.</span></span> <span data-ttu-id="1888f-137">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-137">Role assignment name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-138">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-138">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-139">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="1888f-139">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid) As Task(Of RoleAssignmentDeleteResult)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteAsync (operations, scope, roleAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-140">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-140">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-141">Required.</span></span> <span data-ttu-id="1888f-142">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-142">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-143">Required.</span></span> <span data-ttu-id="1888f-144">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-144">Role assignment name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-145">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-145">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-146">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="1888f-146">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult DeleteById (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult DeleteById(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteById(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteById (operations As IRoleAssignmentOperations, roleAssignmentId As String) As RoleAssignmentDeleteResult" />
      <MemberSignature Language="F#" Value="static member DeleteById : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteById (operations, roleAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-147">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-147">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-148">Required.</span></span> <span data-ttu-id="1888f-149">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-149">Role assignment Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-150">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-150">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-151">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="1888f-151">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteByIdAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteByIdAsync (operations As IRoleAssignmentOperations, roleAssignmentId As String) As Task(Of RoleAssignmentDeleteResult)" />
      <MemberSignature Language="F#" Value="static member DeleteByIdAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.DeleteByIdAsync (operations, roleAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-152">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-152">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-153">Required.</span></span> <span data-ttu-id="1888f-154">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-154">Role assignment Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-155">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-155">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-156">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="1888f-156">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult Get (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult Get(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Get(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid) As RoleAssignmentGetResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.Get (operations, scope, roleAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-157">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-157">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-158">Required.</span></span> <span data-ttu-id="1888f-159">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-159">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-160">Required.</span></span> <span data-ttu-id="1888f-161">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-161">Role assignment name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-162">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-162">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-163">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="1888f-163">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Guid roleAssignmentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, valuetype System.Guid roleAssignmentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRoleAssignmentOperations, scope As String, roleAssignmentName As Guid) As Task(Of RoleAssignmentGetResult)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetAsync (operations, scope, roleAssignmentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-164">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-164">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-165">Required.</span></span> <span data-ttu-id="1888f-166">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-166">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="1888f-167">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-167">Required.</span></span> <span data-ttu-id="1888f-168">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-168">Role assignment name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-169">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-169">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-170">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="1888f-170">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult GetById (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult GetById(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetById(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IRoleAssignmentOperations, roleAssignmentId As String) As RoleAssignmentGetResult" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetById (operations, roleAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-171">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-171">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-172">Required.</span></span> <span data-ttu-id="1888f-173">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-173">Role assignment Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-174">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-174">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-175">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="1888f-175">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string roleAssignmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByIdAsync (operations As IRoleAssignmentOperations, roleAssignmentId As String) As Task(Of RoleAssignmentGetResult)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.GetByIdAsync (operations, roleAssignmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="roleAssignmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-176">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-176">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="roleAssignmentId">
            <span data-ttu-id="1888f-177">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-177">Required.</span></span> <span data-ttu-id="1888f-178">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="1888f-178">Role assignment Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-179">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="1888f-179">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-180">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="1888f-180">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult List (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult List(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.List(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRoleAssignmentOperations, parameters As ListAssignmentsFilterParameters) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.List (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-181">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-181">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-182">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-182">Optional.</span></span> <span data-ttu-id="1888f-183">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-183">List operation filters.</span></span> <span data-ttu-id="1888f-184">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-184">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-185">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-185">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-186">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-186">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IRoleAssignmentOperations, parameters As ListAssignmentsFilterParameters) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-187">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-187">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-188">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-188">Optional.</span></span> <span data-ttu-id="1888f-189">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-189">List operation filters.</span></span> <span data-ttu-id="1888f-190">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-190">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-191">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-191">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-192">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-192">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResource">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResource (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResource(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResource(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.ResourceIdentity,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResource (operations As IRoleAssignmentOperations, resourceGroupName As String, identity As ResourceIdentity, parameters As ListAssignmentsFilterParameters) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForResource : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.ResourceIdentity * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResource (operations, resourceGroupName, identity, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-193">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-193">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1888f-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-194">Required.</span></span> <span data-ttu-id="1888f-195">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1888f-195">The name of the resource group.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="1888f-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-196">Required.</span></span> <span data-ttu-id="1888f-197">Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1888f-197">Resource identity.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-198">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-198">Optional.</span></span> <span data-ttu-id="1888f-199">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-199">List operation filters.</span></span> <span data-ttu-id="1888f-200">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressource zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-200">If null will return all role assignments at, above or below the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-201">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-201">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-202">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-202">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.ResourceIdentity,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceAsync (operations As IRoleAssignmentOperations, resourceGroupName As String, identity As ResourceIdentity, parameters As ListAssignmentsFilterParameters) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.ResourceIdentity * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceAsync (operations, resourceGroupName, identity, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-203">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-203">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1888f-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-204">Required.</span></span> <span data-ttu-id="1888f-205">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1888f-205">The name of the resource group.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="1888f-206">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-206">Required.</span></span> <span data-ttu-id="1888f-207">Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1888f-207">Resource identity.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-208">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-208">Optional.</span></span> <span data-ttu-id="1888f-209">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-209">List operation filters.</span></span> <span data-ttu-id="1888f-210">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressource zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-210">If null will return all role assignments at, above or below the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-211">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-211">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-212">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-212">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceGroup (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceGroup(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroup(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroup (operations As IRoleAssignmentOperations, resourceGroupName As String, parameters As ListAssignmentsFilterParameters) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroup : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroup (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-213">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-213">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1888f-214">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-214">Optional.</span></span> <span data-ttu-id="1888f-215">Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1888f-215">Resource group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-216">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-216">Optional.</span></span> <span data-ttu-id="1888f-217">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-217">List operation filters.</span></span> <span data-ttu-id="1888f-218">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressourcengruppe zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-218">If null will return all role assignments at, above or below the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-219">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-219">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-220">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-220">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupAsync (operations As IRoleAssignmentOperations, resourceGroupName As String, parameters As ListAssignmentsFilterParameters) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-221">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-221">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1888f-222">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-222">Optional.</span></span> <span data-ttu-id="1888f-223">Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1888f-223">Resource group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-224">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-224">Optional.</span></span> <span data-ttu-id="1888f-225">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-225">List operation filters.</span></span> <span data-ttu-id="1888f-226">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressourcengruppe zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-226">If null will return all role assignments at, above or below the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-227">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-227">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-228">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-228">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceGroupNext (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceGroupNext(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupNext(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupNext (operations As IRoleAssignmentOperations, nextLink As String) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNext : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-229">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-229">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-230">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-230">Required.</span></span> <span data-ttu-id="1888f-231">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-231">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-232">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-232">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-233">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-233">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupNextAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupNextAsync (operations As IRoleAssignmentOperations, nextLink As String) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupNextAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceGroupNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-234">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-234">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-235">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-235">Required.</span></span> <span data-ttu-id="1888f-236">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-236">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-237">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-237">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-238">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-238">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceNext (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForResourceNext(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceNext(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceNext (operations As IRoleAssignmentOperations, nextLink As String) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForResourceNext : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-239">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-239">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-240">Required.</span></span> <span data-ttu-id="1888f-241">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-241">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-242">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-242">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-243">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-243">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceNextAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceNextAsync (operations As IRoleAssignmentOperations, nextLink As String) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceNextAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForResourceNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-244">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-244">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-245">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-245">Required.</span></span> <span data-ttu-id="1888f-246">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-246">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-247">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-247">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-248">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-248">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForScope (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForScope(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScope(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForScope (operations As IRoleAssignmentOperations, scope As String, parameters As ListAssignmentsFilterParameters) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForScope : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScope (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-249">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-249">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-250">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-250">Required.</span></span> <span data-ttu-id="1888f-251">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-251">Scope.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-252">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-252">Optional.</span></span> <span data-ttu-id="1888f-253">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-253">List operation filters.</span></span> <span data-ttu-id="1888f-254">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-254">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-255">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-255">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-256">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-256">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string scope, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForScopeAsync (operations As IRoleAssignmentOperations, scope As String, parameters As ListAssignmentsFilterParameters) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForScopeAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeAsync (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-257">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-257">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1888f-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-258">Required.</span></span> <span data-ttu-id="1888f-259">Bereich.</span><span class="sxs-lookup"><span data-stu-id="1888f-259">Scope.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1888f-260">Optional.</span><span class="sxs-lookup"><span data-stu-id="1888f-260">Optional.</span></span> <span data-ttu-id="1888f-261">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="1888f-261">List operation filters.</span></span> <span data-ttu-id="1888f-262">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="1888f-262">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-263">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-263">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-264">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-264">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForScopeNext (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListForScopeNext(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeNext(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForScopeNext (operations As IRoleAssignmentOperations, nextLink As String) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListForScopeNext : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-265">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-265">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-266">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-266">Required.</span></span> <span data-ttu-id="1888f-267">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-267">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-268">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-268">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-269">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-269">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeNextAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForScopeNextAsync (operations As IRoleAssignmentOperations, nextLink As String) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListForScopeNextAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListForScopeNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-270">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-270">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-271">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-271">Required.</span></span> <span data-ttu-id="1888f-272">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-272">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-273">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-273">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-274">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-274">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListNext (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult ListNext(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListNext(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRoleAssignmentOperations, nextLink As String) As RoleAssignmentListResult" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-275">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-275">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-276">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-276">Required.</span></span> <span data-ttu-id="1888f-277">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-277">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-278">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-278">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-279">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-279">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync (this Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync(class Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IRoleAssignmentOperations, nextLink As String) As Task(Of RoleAssignmentListResult)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleAssignmentOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1888f-280">Verweis auf die Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span><span class="sxs-lookup"><span data-stu-id="1888f-280">Reference to the Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1888f-281">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1888f-281">Required.</span></span> <span data-ttu-id="1888f-282">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1888f-282">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1888f-283">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="1888f-283">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1888f-284">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="1888f-284">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>