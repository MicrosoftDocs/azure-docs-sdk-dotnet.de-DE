<Type Name="AutoUserSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification">
  <TypeSignature Language="C#" Value="public class AutoUserSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoUserSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoUserSpecification" />
  <TypeSignature Language="F#" Value="type AutoUserSpecification = class" />
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
            Gibt die Parameter für den Auto-Benutzer, der eine Aufgabe auf die Batch-Dienst ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AutoUserSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; scope = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; scope, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; elevationLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.AutoUserScope},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ElevationLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scope As Nullable(Of AutoUserScope) = null, Optional elevationLevel As Nullable(Of ElevationLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification (scope, elevationLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scope" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt;" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="scope">Der Bereich für den Benutzer automatisch</param>
        <param name="elevationLevel">Die Ebene der Erhöhung der Rechte des Benutzers automatisch.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoUserSpecification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ebene der Erhöhung der Rechte des Benutzers automatisch.
            </summary>
        <value>To be added.</value>
        <remarks>
            NonAdmin - der Auto-Benutzer ist ein Standardbenutzer ohne erhöhte Zugriffsrechte. Admin - der Auto-Benutzer ist ein Benutzer mit erweiterten Zugriff und arbeitet mit vollständigen Administratorberechtigungen. Der Standardwert ist NonAdmin. Folgende Werte sind möglich: "NonAdmin", "Admin"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As Nullable(Of AutoUserScope)" />
      <MemberSignature Language="F#" Value="member this.Scope : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.AutoUserScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bereich für den Benutzer automatisch
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist die Aufgabe. Folgende Werte sind möglich: "Aufgabe", "Pool"
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>