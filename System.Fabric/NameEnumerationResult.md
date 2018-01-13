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
      <para>Eine Auflistung von Service Fabric-Namen, wie vom <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />.</para>
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
          <para>Gibt an, ob weitere verbleibenden Seiten vorhanden sind. Wenn der Wert "true", klicken Sie dann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" /> aufgerufen werden, um die nächste Seite zu erhalten.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> verfügt die Enumeration mehr Daten; <languageKeyword>"false"</languageKeyword> andernfalls.</para>
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
          <para>Gibt an, ob ein beliebiger Name unter dem angegebenen Namen während der Enumeration geändert wurde. Wenn eine Änderung aufgetreten ist, ist dieser Eigenschaftswert "true".</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> ist die Enumeration bemüht; <languageKeyword>"false"</languageKeyword> andernfalls.</para>
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
          <para>Gibt an, ob ein beliebiger Name unter dem angegebenen Namen während der Enumeration geändert wurde. Wenn eine Änderung aufgetreten ist, ist der Wert dieser Eigenschaft "false".</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> ist die Enumeration konsistent; <languageKeyword>"false"</languageKeyword> andernfalls.</para>
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
          <para>Gibt an, ob es keine weiteren verbleibenden Seiten sind.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> , wenn die Enumeration abgeschlossen ist; <languageKeyword>"false"</languageKeyword> andernfalls.</para>
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
          <para>Gibt an, ob das enumerationsergebnis gültig ist. Verwenden Sie nicht das Ergebnis aus, wenn er nicht gültig ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn das enumerationsergebnis gültig ist. <languageKeyword>"false"</languageKeyword> andernfalls.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>