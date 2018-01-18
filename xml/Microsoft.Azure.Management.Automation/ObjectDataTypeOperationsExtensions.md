<Type Name="ObjectDataTypeOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ObjectDataTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ObjectDataTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ObjectDataTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ObjectDataTypeOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
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
    <Member MemberName="ListFieldsByModuleAndType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse ListFieldsByModuleAndType (this Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse ListFieldsByModuleAndType(class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByModuleAndType(Microsoft.Azure.Management.Automation.IObjectDataTypeOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFieldsByModuleAndType (operations As IObjectDataTypeOperations, resourceGroupName As String, automationAccount As String, moduleName As String, typeName As String) As TypeFieldListResponse" />
      <MemberSignature Language="F#" Value="static member ListFieldsByModuleAndType : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse" Usage="Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByModuleAndType (operations, resourceGroupName, automationAccount, moduleName, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="29ec6-101">Verweis auf die Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="29ec6-101">Reference to the Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="29ec6-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-102">Required.</span></span> <span data-ttu-id="29ec6-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="29ec6-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="29ec6-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-104">Required.</span></span> <span data-ttu-id="29ec6-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="29ec6-105">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="29ec6-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-106">Required.</span></span> <span data-ttu-id="29ec6-107">Der Name des Moduls.</span><span class="sxs-lookup"><span data-stu-id="29ec6-107">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="29ec6-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-108">Required.</span></span> <span data-ttu-id="29ec6-109">Der Name des Typs.</span><span class="sxs-lookup"><span data-stu-id="29ec6-109">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="29ec6-110">Abgerufen Sie eine Liste der Felder eines bestimmten Typs Modulname identifizierte werden.</span><span class="sxs-lookup"><span data-stu-id="29ec6-110">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="29ec6-111">(siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="29ec6-111">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="29ec6-112">Das Antwort-Modell für die Liste Felder-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="29ec6-112">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFieldsByModuleAndTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByModuleAndTypeAsync (this Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByModuleAndTypeAsync(class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByModuleAndTypeAsync(Microsoft.Azure.Management.Automation.IObjectDataTypeOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFieldsByModuleAndTypeAsync (operations As IObjectDataTypeOperations, resourceGroupName As String, automationAccount As String, moduleName As String, typeName As String) As Task(Of TypeFieldListResponse)" />
      <MemberSignature Language="F#" Value="static member ListFieldsByModuleAndTypeAsync : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations * string * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByModuleAndTypeAsync (operations, resourceGroupName, automationAccount, moduleName, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="29ec6-113">Verweis auf die Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="29ec6-113">Reference to the Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="29ec6-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-114">Required.</span></span> <span data-ttu-id="29ec6-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="29ec6-115">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="29ec6-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-116">Required.</span></span> <span data-ttu-id="29ec6-117">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="29ec6-117">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="29ec6-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-118">Required.</span></span> <span data-ttu-id="29ec6-119">Der Name des Moduls.</span><span class="sxs-lookup"><span data-stu-id="29ec6-119">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="29ec6-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-120">Required.</span></span> <span data-ttu-id="29ec6-121">Der Name des Typs.</span><span class="sxs-lookup"><span data-stu-id="29ec6-121">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="29ec6-122">Abgerufen Sie eine Liste der Felder eines bestimmten Typs Modulname identifizierte werden.</span><span class="sxs-lookup"><span data-stu-id="29ec6-122">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="29ec6-123">(siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="29ec6-123">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="29ec6-124">Das Antwort-Modell für die Liste Felder-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="29ec6-124">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFieldsByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse ListFieldsByType (this Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse ListFieldsByType(class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByType(Microsoft.Azure.Management.Automation.IObjectDataTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFieldsByType (operations As IObjectDataTypeOperations, resourceGroupName As String, automationAccount As String, typeName As String) As TypeFieldListResponse" />
      <MemberSignature Language="F#" Value="static member ListFieldsByType : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse" Usage="Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByType (operations, resourceGroupName, automationAccount, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="29ec6-125">Verweis auf die Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="29ec6-125">Reference to the Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="29ec6-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-126">Required.</span></span> <span data-ttu-id="29ec6-127">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="29ec6-127">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="29ec6-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-128">Required.</span></span> <span data-ttu-id="29ec6-129">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="29ec6-129">The automation account name.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="29ec6-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-130">Required.</span></span> <span data-ttu-id="29ec6-131">Der Name des Typs.</span><span class="sxs-lookup"><span data-stu-id="29ec6-131">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="29ec6-132">Rufen Sie eine Liste von Feldern eines bestimmten Typs über alle Module auf zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="29ec6-132">Retrieve a list of fields of a given type across all accessible modules.</span></span>  <span data-ttu-id="29ec6-133">(siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="29ec6-133">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="29ec6-134">Das Antwort-Modell für die Liste Felder-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="29ec6-134">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFieldsByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByTypeAsync (this Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByTypeAsync(class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations operations, string resourceGroupName, string automationAccount, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByTypeAsync(Microsoft.Azure.Management.Automation.IObjectDataTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListFieldsByTypeAsync (operations As IObjectDataTypeOperations, resourceGroupName As String, automationAccount As String, typeName As String) As Task(Of TypeFieldListResponse)" />
      <MemberSignature Language="F#" Value="static member ListFieldsByTypeAsync : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ObjectDataTypeOperationsExtensions.ListFieldsByTypeAsync (operations, resourceGroupName, automationAccount, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="29ec6-135">Verweis auf die Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span><span class="sxs-lookup"><span data-stu-id="29ec6-135">Reference to the Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="29ec6-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-136">Required.</span></span> <span data-ttu-id="29ec6-137">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="29ec6-137">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="29ec6-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-138">Required.</span></span> <span data-ttu-id="29ec6-139">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="29ec6-139">The automation account name.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="29ec6-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="29ec6-140">Required.</span></span> <span data-ttu-id="29ec6-141">Der Name des Typs.</span><span class="sxs-lookup"><span data-stu-id="29ec6-141">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="29ec6-142">Rufen Sie eine Liste von Feldern eines bestimmten Typs über alle Module auf zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="29ec6-142">Retrieve a list of fields of a given type across all accessible modules.</span></span>  <span data-ttu-id="29ec6-143">(siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="29ec6-143">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="29ec6-144">Das Antwort-Modell für die Liste Felder-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="29ec6-144">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>