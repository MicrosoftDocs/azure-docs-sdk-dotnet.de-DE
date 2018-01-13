<Type Name="AutoUserSpecification" FullName="Microsoft.Azure.Batch.AutoUserSpecification">
  <TypeSignature Language="C#" Value="public class AutoUserSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoUserSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoUserSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoUserSpecification" />
  <TypeSignature Language="F#" Value="type AutoUserSpecification = class&#xA;    interface ITransportObjectProvider&lt;AutoUserSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt die Parameter für den Auto-Benutzer, der ein Task auf die Batch-Dienst ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification (Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt; scope = null, Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.AutoUserScope&gt; scope, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AutoUserSpecification.#ctor(System.Nullable{Microsoft.Azure.Batch.Common.AutoUserScope},System.Nullable{Microsoft.Azure.Batch.Common.ElevationLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scope As Nullable(Of AutoUserScope) = null, Optional elevationLevel As Nullable(Of ElevationLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.AutoUserSpecification : Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; -&gt; Microsoft.Azure.Batch.AutoUserSpecification" Usage="new Microsoft.Azure.Batch.AutoUserSpecification (scope, elevationLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scope" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt;" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="scope">Der Bereich für den Benutzer automatisch. Wenn nicht angegeben, ist die Standardeinstellung <see cref="F:Microsoft.Azure.Batch.Common.AutoUserScope.Task" />.</param>
        <param name="elevationLevel">Die Ebene der Erhöhung der Rechte des Benutzers automatisch. Wenn nicht angegeben, ist die Standardeinstellung <see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.AutoUserSpecification" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoUserSpecification.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;" Usage="Microsoft.Azure.Batch.AutoUserSpecification.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Höhe des Benutzers automatisch ab. Wenn nicht angegeben, ist die Standardeinstellung <see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt; Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.AutoUserScope&gt; Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoUserSpecification.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As Nullable(Of AutoUserScope)" />
      <MemberSignature Language="F#" Value="member this.Scope : Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt;" Usage="Microsoft.Azure.Batch.AutoUserSpecification.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.AutoUserScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereich für den Benutzer automatisch ab. Wenn nicht angegeben, ist die Standardeinstellung <see cref="F:Microsoft.Azure.Batch.Common.AutoUserScope.Task" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>