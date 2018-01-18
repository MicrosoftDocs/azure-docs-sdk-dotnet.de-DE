<Type Name="TagsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TagsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TagsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TagsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TagsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b4443-101">Erweiterungsmethoden für TagsOperations.</span><span class="sxs-lookup"><span data-stu-id="b4443-101">Extension methods for TagsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.TagDetails CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.TagDetails CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITagsOperations, tagName As String) As TagDetails" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.TagDetails" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdate (operations, tagName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TagDetails</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-102">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-103">Der Name des Tags zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-103">The name of the tag to create.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-104">Erstellt ein Tag im Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b4443-104">Creates a tag in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4443-105">Der Tagname darf höchstens 512 Zeichen und Groß-/Kleinschreibung beachtet wird.</span><span class="sxs-lookup"><span data-stu-id="b4443-105">The tag name can have a maximum of 512 characters and is case insensitive.</span></span>
            <span data-ttu-id="b4443-106">Von Azure erstellte Tagnamen weisen die Präfixe Microsoft, Azure oder Windows.</span><span class="sxs-lookup"><span data-stu-id="b4443-106">Tag names created by Azure have prefixes of microsoft, azure, or windows.</span></span>
            <span data-ttu-id="b4443-107">Sie können keine Tags mit einem dieser Präfixe erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-107">You cannot create tags with one of these prefixes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateAsync (operations, tagName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-108">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-109">Der Name des Tags zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-109">The name of the tag to create.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-111">Erstellt ein Tag im Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b4443-111">Creates a tag in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4443-112">Der Tagname darf höchstens 512 Zeichen und Groß-/Kleinschreibung beachtet wird.</span><span class="sxs-lookup"><span data-stu-id="b4443-112">The tag name can have a maximum of 512 characters and is case insensitive.</span></span>
            <span data-ttu-id="b4443-113">Von Azure erstellte Tagnamen weisen die Präfixe Microsoft, Azure oder Windows.</span><span class="sxs-lookup"><span data-stu-id="b4443-113">Tag names created by Azure have prefixes of microsoft, azure, or windows.</span></span>
            <span data-ttu-id="b4443-114">Sie können keine Tags mit einem dieser Präfixe erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-114">You cannot create tags with one of these prefixes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateValue">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.TagValue CreateOrUpdateValue (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.TagValue CreateOrUpdateValue(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValue(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateValue : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.TagValue" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValue (operations, tagName, tagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TagValue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-115">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-116">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-116">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="b4443-117">Der Wert des Tags zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-117">The value of the tag to create.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-118">Erstellt einen Tagwert.</span><span class="sxs-lookup"><span data-stu-id="b4443-118">Creates a tag value.</span></span> <span data-ttu-id="b4443-119">Der Name des Tags muss bereits vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="b4443-119">The name of the tag must already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateValueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; CreateOrUpdateValueAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; CreateOrUpdateValueAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValueAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateValueAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValueAsync (operations, tagName, tagValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;CreateOrUpdateValueAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-120">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-121">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-121">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="b4443-122">Der Wert des Tags zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b4443-122">The value of the tag to create.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-124">Erstellt einen Tagwert.</span><span class="sxs-lookup"><span data-stu-id="b4443-124">Creates a tag value.</span></span> <span data-ttu-id="b4443-125">Der Name des Tags muss bereits vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="b4443-125">The name of the tag must already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITagsOperations, tagName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.Delete (operations, tagName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-126">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-127">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-127">The name of the tag.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-128">Löscht ein Tag aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b4443-128">Deletes a tag from the subscription.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="b4443-129">Sie müssen alle Werte aus einem ressourcentag entfernen, bevor Sie es löschen können.</span><span class="sxs-lookup"><span data-stu-id="b4443-129">You must remove all values from a resource tag before you can delete it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteAsync (operations, tagName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-130">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-131">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-131">The name of the tag.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-133">Löscht ein Tag aus dem Abonnement.</span><span class="sxs-lookup"><span data-stu-id="b4443-133">Deletes a tag from the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b4443-134">Sie müssen alle Werte aus einem ressourcentag entfernen, bevor Sie es löschen können.</span><span class="sxs-lookup"><span data-stu-id="b4443-134">You must remove all values from a resource tag before you can delete it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteValue">
      <MemberSignature Language="C#" Value="public static void DeleteValue (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteValue(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValue(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteValue (operations As ITagsOperations, tagName As String, tagValue As String)" />
      <MemberSignature Language="F#" Value="static member DeleteValue : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValue (operations, tagName, tagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-135">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-136">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-136">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="b4443-137">Der Wert des Tags zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b4443-137">The value of the tag to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-138">Löscht einen Tagwert.</span><span class="sxs-lookup"><span data-stu-id="b4443-138">Deletes a tag value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteValueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteValueAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteValueAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValueAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteValueAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValueAsync (operations, tagName, tagValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;DeleteValueAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-139">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="b4443-140">Der Name des Tags.</span><span class="sxs-lookup"><span data-stu-id="b4443-140">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="b4443-141">Der Wert des Tags zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b4443-141">The value of the tag to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-143">Löscht einen Tagwert.</span><span class="sxs-lookup"><span data-stu-id="b4443-143">Deletes a tag value.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; List (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; List(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ITagsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITagsOperations) As IPage(Of TagDetails)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ITagsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-144">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-145">Ruft die Namen und Werte aller Ressourcentags, die in einem Abonnement definiert sind.</span><span class="sxs-lookup"><span data-stu-id="b4443-145">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-146">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-148">Ruft die Namen und Werte aller Ressourcentags, die in einem Abonnement definiert sind.</span><span class="sxs-lookup"><span data-stu-id="b4443-148">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ITagsOperations, nextPageLink As String) As IPage(Of TagDetails)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b4443-150">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b4443-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-151">Ruft die Namen und Werte aller Ressourcentags, die in einem Abonnement definiert sind.</span><span class="sxs-lookup"><span data-stu-id="b4443-151">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b4443-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="b4443-152">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b4443-153">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="b4443-153">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b4443-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b4443-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b4443-155">Ruft die Namen und Werte aller Ressourcentags, die in einem Abonnement definiert sind.</span><span class="sxs-lookup"><span data-stu-id="b4443-155">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>