<Type Name="NameEnumerationResult" FullName="System.Fabric.NameEnumerationResult">
  <TypeSignature Language="C#" Value="public class NameEnumerationResult : System.Collections.ObjectModel.Collection&lt;Uri&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NameEnumerationResult extends System.Collections.ObjectModel.Collection`1&lt;class System.Uri&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NameEnumerationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NameEnumerationResult&#xA;Inherits Collection(Of Uri)" />
  <TypeSignature Language="F#" Value="type NameEnumerationResult = class&#xA;    inherit Collection&lt;Uri&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.Collection&lt;System.Uri&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.Uri</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="51a1a-101">Eine Auflistung von Service Fabric-Namen, wie vom <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />.</span><span class="sxs-lookup"><span data-stu-id="51a1a-101">A collection of Service Fabric names, as returned by <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasMoreData">
      <MemberSignature Language="C#" Value="public bool HasMoreData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.HasMoreData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreData As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreData : bool" Usage="System.Fabric.NameEnumerationResult.HasMoreData" />
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
          <para><span data-ttu-id="51a1a-102">Gibt an, ob weitere verbleibenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="51a1a-102">Indicates whether there are more remaining pages.</span></span> <span data-ttu-id="51a1a-103">Wenn der Wert "true", klicken Sie dann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" /> aufgerufen werden, um die nächste Seite zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="51a1a-103">If the value is true, then <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" /> can be called to acquire the next page.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="51a1a-104"><languageKeyword>"true"</languageKeyword> verfügt die Enumeration mehr Daten; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="51a1a-104"><languageKeyword>true</languageKeyword> if the enumeration has more data; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBestEffort">
      <MemberSignature Language="C#" Value="public bool IsBestEffort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBestEffort" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsBestEffort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBestEffort As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBestEffort : bool" Usage="System.Fabric.NameEnumerationResult.IsBestEffort" />
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
          <para><span data-ttu-id="51a1a-105">Gibt an, ob ein beliebiger Name unter dem angegebenen Namen während der Enumeration geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="51a1a-105">Indicates whether any name under the given name has been modified during the enumeration.</span></span> <span data-ttu-id="51a1a-106">Wenn eine Änderung aufgetreten ist, ist dieser Eigenschaftswert "true".</span><span class="sxs-lookup"><span data-stu-id="51a1a-106">If there was a modification, this property value is true.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="51a1a-107"><languageKeyword>"true"</languageKeyword> ist die Enumeration bemüht; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="51a1a-107"><languageKeyword>true</languageKeyword> if the enumeration is best effort; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsConsistent">
      <MemberSignature Language="C#" Value="public bool IsConsistent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsConsistent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsConsistent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsConsistent As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsConsistent : bool" Usage="System.Fabric.NameEnumerationResult.IsConsistent" />
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
          <para><span data-ttu-id="51a1a-108">Gibt an, ob ein beliebiger Name unter dem angegebenen Namen während der Enumeration geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="51a1a-108">Indicates whether any name under the given name has been modified during the enumeration.</span></span> <span data-ttu-id="51a1a-109">Wenn eine Änderung aufgetreten ist, ist der Wert dieser Eigenschaft "false".</span><span class="sxs-lookup"><span data-stu-id="51a1a-109">If there was a modification, this property value  is false.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="51a1a-110"><languageKeyword>"true"</languageKeyword> ist die Enumeration konsistent; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="51a1a-110"><languageKeyword>true</languageKeyword> if the enumeration is consistent; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFinished">
      <MemberSignature Language="C#" Value="public bool IsFinished { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFinished" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsFinished" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsFinished As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFinished : bool" Usage="System.Fabric.NameEnumerationResult.IsFinished" />
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
          <para><span data-ttu-id="51a1a-111">Gibt an, ob es keine weiteren verbleibenden Seiten sind.</span><span class="sxs-lookup"><span data-stu-id="51a1a-111">Indicates whether there are no more remaining pages.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="51a1a-112"><languageKeyword>"true"</languageKeyword> , wenn die Enumeration abgeschlossen ist; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="51a1a-112"><languageKeyword>true</languageKeyword> if the enumeration is finished; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public bool IsValid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsValid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NameEnumerationResult.IsValid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsValid As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsValid : bool" Usage="System.Fabric.NameEnumerationResult.IsValid" />
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
          <para><span data-ttu-id="51a1a-113">Gibt an, ob das enumerationsergebnis gültig ist.</span><span class="sxs-lookup"><span data-stu-id="51a1a-113">Indicates whether the enumeration result is valid.</span></span> <span data-ttu-id="51a1a-114">Verwenden Sie nicht das Ergebnis aus, wenn er nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="51a1a-114">Do not use the result, if it is not valid.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="51a1a-115"><languageKeyword>"true"</languageKeyword> Wenn das enumerationsergebnis gültig ist. <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="51a1a-115"><languageKeyword>true</languageKeyword> if the enumeration result is valid; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>