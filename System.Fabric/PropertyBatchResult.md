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
      <para>Gibt den Batch mit den Ergebnissen aus der <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> -Methodenaufruf.</para>
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
          <para>Ruft die fehlgeschlagene Operation-Ausnahme ab. Dieser Parameter enthält die Ausnahme, die ausgelöst wird, das erste nicht erfolgreich <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt im Batch.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Exception" />zurück.</para>
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
          <para>Ruft den Index des fehlgeschlagenen Vorgangs. Dieser Parameter enthält den Index der der nicht erfolgreichen <see cref="T:System.Fabric.PropertyBatchOperation" /> im Batch.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Int32" />zurück.</para>
        </value>
        <remarks>
          <para>Beachten Sie, wenn keiner der Vorgänge im Batch ein Fehler auftritt, wird diese Eigenschaft auf-1 festgelegt werden.</para>
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
          <para>Ein <see cref="T:System.Int32" /> , gibt, die den Index im Batch, die gesendet wurde.</para>
        </param>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.NamedProperty" /> von zurückgegebene Objekt der <see cref="T:System.Fabric.PropertyBatchOperation" /> im angegebenen Index.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.NamedProperty" />zurück.</para>
        </returns>
        <remarks>
          <para>Beachten Sie, dass, ob <see cref="T:System.Fabric.NamedPropertyMetadata" /> wird zurückgegeben, ist abhängig von der <languagekeyword>IncludeValues</languagekeyword> Argument an die <see cref="T:System.Fabric.GetPropertyOperation" />. Gibt einen Fehler zurück, wenn der Vorgang einen anderen Typ aufweist, als angegeben.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>