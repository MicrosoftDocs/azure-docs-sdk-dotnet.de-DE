<Type Name="TransformationsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TransformationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TransformationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TransformationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TransformationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="757f9-101">Erweiterungsmethoden für TransformationsOperations.</span><span class="sxs-lookup"><span data-stu-id="757f9-101">Extension methods for TransformationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplace (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="transformation">
            <span data-ttu-id="757f9-103">Die Definition der Transformation, die zum Erstellen Sie eine neue Transformation oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-103">The definition of the transformation that will be used to create a new transformation or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-104">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-104">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-105">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-105">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-106">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-106">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-107">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-107">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="757f9-108">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-108">The ETag of the transformation.</span></span> <span data-ttu-id="757f9-109">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="757f9-109">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="757f9-110">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="757f9-110">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="757f9-111">Legen Sie auf "\*" um eine neue Transformation erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Transformation zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="757f9-111">Set to '\*' to allow a new transformation to be created, but to prevent updating an existing transformation.</span></span> <span data-ttu-id="757f9-112">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="757f9-112">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-113">Erstellt eine Transformation oder eine bereits vorhandene Transformation unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="757f9-113">Creates a transformation or replaces an already existing transformation under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.CreateOrReplaceAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-114">The operations group for this extension method.</span></span>
            </param>
        <param name="transformation">
            <span data-ttu-id="757f9-115">Die Definition der Transformation, die zum Erstellen Sie eine neue Transformation oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-115">The definition of the transformation that will be used to create a new transformation or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-116">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-118">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-118">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-119">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-119">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="757f9-120">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-120">The ETag of the transformation.</span></span> <span data-ttu-id="757f9-121">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="757f9-121">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="757f9-122">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="757f9-122">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="757f9-123">Legen Sie auf "\*" um eine neue Transformation erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Transformation zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="757f9-123">Set to '\*' to allow a new transformation to be created, but to prevent updating an existing transformation.</span></span> <span data-ttu-id="757f9-124">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="757f9-124">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757f9-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757f9-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-126">Erstellt eine Transformation oder eine bereits vorhandene Transformation unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="757f9-126">Creates a transformation or replaces an already existing transformation under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Get(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITransformationsOperations, resourceGroupName As String, jobName As String, transformationName As String) As Transformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Get (operations, resourceGroupName, jobName, transformationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-128">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-128">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-129">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-129">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-130">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-130">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-131">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-131">The name of the transformation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-132">Ruft Details zu der angegebenen Transformation ab.</span><span class="sxs-lookup"><span data-stu-id="757f9-132">Gets details about the specified transformation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, string resourceGroupName, string jobName, string transformationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, transformationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-134">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-135">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-136">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-136">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-137">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-137">The name of the transformation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757f9-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757f9-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-139">Ruft Details zu der angegebenen Transformation ab.</span><span class="sxs-lookup"><span data-stu-id="757f9-139">Gets details about the specified transformation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Update(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.Update (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-140">The operations group for this extension method.</span></span>
            </param>
        <param name="transformation">
            <span data-ttu-id="757f9-141">Eine Transformationsobjekt.</span><span class="sxs-lookup"><span data-stu-id="757f9-141">A Transformation object.</span></span> <span data-ttu-id="757f9-142">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in die vorhandene Transformation (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="757f9-142">The properties specified here will overwrite the corresponding properties in the existing transformation (ie. Those properties will be updated).</span></span> <span data-ttu-id="757f9-143">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Transformation identisch bleibt und als Ergebnis dieser PATCH-Vorgang nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-143">Any properties that are set to null here will mean that the corresponding property in the existing transformation will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-144">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-145">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-146">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-146">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-147">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-147">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="757f9-148">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-148">The ETag of the transformation.</span></span> <span data-ttu-id="757f9-149">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="757f9-149">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="757f9-150">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="757f9-150">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-151">Aktualisiert eine vorhandene Transformation unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="757f9-151">Updates an existing transformation under an existing streaming job.</span></span> <span data-ttu-id="757f9-152">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="757f9-152">This can be used to partially update (ie.</span></span> <span data-ttu-id="757f9-153">Aktualisieren Sie eine oder zwei Eigenschaften) eine Transformation ohne den Rest der Definition der Auftrag oder Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-153">update one or two properties) a transformation without affecting the rest the job or transformation definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions.UpdateAsync (operations, transformation, resourceGroupName, jobName, transformationName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.TransformationsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" RefType="this" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757f9-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757f9-154">The operations group for this extension method.</span></span>
            </param>
        <param name="transformation">
            <span data-ttu-id="757f9-155">Eine Transformationsobjekt.</span><span class="sxs-lookup"><span data-stu-id="757f9-155">A Transformation object.</span></span> <span data-ttu-id="757f9-156">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in die vorhandene Transformation (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="757f9-156">The properties specified here will overwrite the corresponding properties in the existing transformation (ie. Those properties will be updated).</span></span> <span data-ttu-id="757f9-157">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Transformation identisch bleibt und als Ergebnis dieser PATCH-Vorgang nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-157">Any properties that are set to null here will mean that the corresponding property in the existing transformation will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757f9-158">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="757f9-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="757f9-159">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="757f9-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="757f9-160">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="757f9-160">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="757f9-161">Der Name der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-161">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="757f9-162">Das ETag der Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-162">The ETag of the transformation.</span></span> <span data-ttu-id="757f9-163">Lassen Sie diesen Wert, um die aktuelle Transformation immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="757f9-163">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="757f9-164">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="757f9-164">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757f9-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757f9-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757f9-166">Aktualisiert eine vorhandene Transformation unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="757f9-166">Updates an existing transformation under an existing streaming job.</span></span> <span data-ttu-id="757f9-167">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="757f9-167">This can be used to partially update (ie.</span></span> <span data-ttu-id="757f9-168">Aktualisieren Sie eine oder zwei Eigenschaften) eine Transformation ohne den Rest der Definition der Auftrag oder Transformation.</span><span class="sxs-lookup"><span data-stu-id="757f9-168">update one or two properties) a transformation without affecting the rest the job or transformation definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>