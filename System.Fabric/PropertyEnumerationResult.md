<Type Name="PropertyEnumerationResult" FullName="System.Fabric.PropertyEnumerationResult">
  <TypeSignature Language="C#" Value="public class PropertyEnumerationResult : System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PropertyEnumerationResult extends System.Collections.ObjectModel.Collection`1&lt;class System.Fabric.NamedProperty&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyEnumerationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PropertyEnumerationResult&#xA;Inherits Collection(Of NamedProperty)" />
  <TypeSignature Language="F#" Value="type PropertyEnumerationResult = class&#xA;    inherit Collection&lt;NamedProperty&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.Fabric.NamedProperty&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Fabric.NamedProperty</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="8efb7-101">Stellt eine Enumeration von Eigenschaften, die von den Eigenschaften-Manager aus einem Vorgang zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="8efb7-101">Represents an enumeration of properties that is returned from an operation by the property manager.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasMoreData">
      <MemberSignature Language="C#" Value="public bool HasMoreData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreData As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreData : bool" Usage="System.Fabric.PropertyEnumerationResult.HasMoreData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8efb7-102">Gibt an, dass weitere verbleibenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="8efb7-102">Indicates that there are more remaining pages.</span></span> 
            <span data-ttu-id="8efb7-103"><see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />sollte aufgerufen werden, um die nächste Seite zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="8efb7-103"><see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" /> should be called to get the next page.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8efb7-104">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8efb7-104">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBestEffort">
      <MemberSignature Language="C#" Value="public bool IsBestEffort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBestEffort" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBestEffort As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBestEffort : bool" Usage="System.Fabric.PropertyEnumerationResult.IsBestEffort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8efb7-105">Gibt an, ob der Name, unter dem angegebenen Namen während der Enumeration geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="8efb7-105">Indicates whether the name under the given name has been modified during the enumeration.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="8efb7-106">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8efb7-106">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8efb7-107">Wenn eine Änderung aufgetreten ist, ist diese Eigenschaft "true".</span><span class="sxs-lookup"><span data-stu-id="8efb7-107">If there was a modification, this property is true.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConsistent">
      <MemberSignature Language="C#" Value="public bool IsConsistent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsConsistent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsConsistent As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsConsistent : bool" Usage="System.Fabric.PropertyEnumerationResult.IsConsistent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8efb7-108">Gibt an, ob die beliebiger Name unter dem angegebenen Namen während der Enumeration geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="8efb7-108">Indicates whether the any name under the given name has been modified during the enumeration.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="8efb7-109">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8efb7-109">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8efb7-110">Wenn eine Änderung aufgetreten ist, ist diese Eigenschaft "false".</span><span class="sxs-lookup"><span data-stu-id="8efb7-110">If there was a modification, this property is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFinished">
      <MemberSignature Language="C#" Value="public bool IsFinished { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFinished" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFinished As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFinished : bool" Usage="System.Fabric.PropertyEnumerationResult.IsFinished" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8efb7-111">Gibt an, dass keine weiteren verbleibenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="8efb7-111">Indicates that there are no more remaining pages.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8efb7-112">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8efb7-112">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="System.Fabric.PropertyEnumerationResult.IsValid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8efb7-113">Gibt an, ob das enumerationsergebnis gültig ist.</span><span class="sxs-lookup"><span data-stu-id="8efb7-113">Indicates whether the enumeration result is valid.</span></span> <span data-ttu-id="8efb7-114">Verwenden Sie nicht das Ergebnis aus, wenn er nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="8efb7-114">Do not use the result if it is not valid.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8efb7-115">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="8efb7-115">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>