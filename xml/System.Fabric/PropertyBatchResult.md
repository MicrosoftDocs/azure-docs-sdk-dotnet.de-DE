<Type Name="PropertyBatchResult" FullName="System.Fabric.PropertyBatchResult">
  <TypeSignature Language="C#" Value="public sealed class PropertyBatchResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PropertyBatchResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyBatchResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PropertyBatchResult" />
  <TypeSignature Language="F#" Value="type PropertyBatchResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="44ed9-101">Gibt den Batch mit den Ergebnissen aus der <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> -Methodenaufruf.</span><span class="sxs-lookup"><span data-stu-id="44ed9-101">Specifies the batch that contains the results from the <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> method call.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedOperationException">
      <MemberSignature Language="C#" Value="public Exception FailedOperationException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception FailedOperationException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchResult.FailedOperationException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedOperationException As Exception" />
      <MemberSignature Language="F#" Value="member this.FailedOperationException : Exception" Usage="System.Fabric.PropertyBatchResult.FailedOperationException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44ed9-102">Ruft die fehlgeschlagene Operation-Ausnahme ab.</span><span class="sxs-lookup"><span data-stu-id="44ed9-102">Gets the failed operation exception.</span></span> <span data-ttu-id="44ed9-103">Dieser Parameter enthält die Ausnahme, die ausgelöst wird, das erste nicht erfolgreich <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt im Batch.</span><span class="sxs-lookup"><span data-stu-id="44ed9-103">This parameter contains the exception thrown due to the first unsuccessful <see cref="T:System.Fabric.PropertyBatchOperation" /> object in the batch.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44ed9-104">Gibt <see cref="T:System.Exception" />zurück.</span><span class="sxs-lookup"><span data-stu-id="44ed9-104">Returns <see cref="T:System.Exception" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedOperationIndex">
      <MemberSignature Language="C#" Value="public int FailedOperationIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedOperationIndex" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchResult.FailedOperationIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedOperationIndex As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedOperationIndex : int" Usage="System.Fabric.PropertyBatchResult.FailedOperationIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44ed9-105">Ruft den Index des fehlgeschlagenen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="44ed9-105">Gets the failed operation index.</span></span> <span data-ttu-id="44ed9-106">Dieser Parameter enthält den Index der der nicht erfolgreichen <see cref="T:System.Fabric.PropertyBatchOperation" /> im Batch.</span><span class="sxs-lookup"><span data-stu-id="44ed9-106">This parameter contains the index of the unsuccessful <see cref="T:System.Fabric.PropertyBatchOperation" /> in the batch.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44ed9-107">Gibt <see cref="T:System.Int32" />zurück.</span><span class="sxs-lookup"><span data-stu-id="44ed9-107">Returns <see cref="T:System.Int32" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="44ed9-108">Beachten Sie, wenn keiner der Vorgänge im Batch ein Fehler auftritt, wird diese Eigenschaft auf-1 festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="44ed9-108">Note that if none of the operations in the batch fail, this property will be set to -1.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public System.Fabric.NamedProperty GetProperty (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.NamedProperty GetProperty(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchResult.GetProperty(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (index As Integer) As NamedProperty" />
      <MemberSignature Language="F#" Value="member this.GetProperty : int -&gt; System.Fabric.NamedProperty" Usage="propertyBatchResult.GetProperty index" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NamedProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="44ed9-109">Ein <see cref="T:System.Int32" /> , gibt, die den Index im Batch, die gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="44ed9-109">An <see cref="T:System.Int32" /> that indicates the index in the batch that was submitted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="44ed9-110">Ruft die <see cref="T:System.Fabric.NamedProperty" /> von zurückgegebene Objekt der <see cref="T:System.Fabric.PropertyBatchOperation" /> im angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="44ed9-110">Gets the <see cref="T:System.Fabric.NamedProperty" /> object that is returned by the <see cref="T:System.Fabric.PropertyBatchOperation" /> in the specified index.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="44ed9-111">Gibt <see cref="T:System.Fabric.NamedProperty" />zurück.</span><span class="sxs-lookup"><span data-stu-id="44ed9-111">Returns <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="44ed9-112">Beachten Sie, dass, ob <see cref="T:System.Fabric.NamedPropertyMetadata" /> wird zurückgegeben, ist abhängig von der <languagekeyword>IncludeValues</languagekeyword> Argument an die <see cref="T:System.Fabric.GetPropertyOperation" />.</span><span class="sxs-lookup"><span data-stu-id="44ed9-112">Note that whether <see cref="T:System.Fabric.NamedPropertyMetadata" /> is returned is dependent on the <languagekeyword>includeValues</languagekeyword> argument to the <see cref="T:System.Fabric.GetPropertyOperation" />.</span></span> <span data-ttu-id="44ed9-113">Gibt einen Fehler zurück, wenn der Vorgang einen anderen Typ aufweist, als angegeben.</span><span class="sxs-lookup"><span data-stu-id="44ed9-113">Returns an error when the operation has a different type than specified.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>