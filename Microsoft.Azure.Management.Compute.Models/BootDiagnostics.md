<Type Name="BootDiagnostics" FullName="Microsoft.Azure.Management.Compute.Models.BootDiagnostics">
  <TypeSignature Language="C#" Value="public class BootDiagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BootDiagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.BootDiagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class BootDiagnostics" />
  <TypeSignature Language="F#" Value="type BootDiagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Startdiagnoseeinstellungen ist eine Debugfunktion Dadurch haben Sie die Konsolenausgabe und Screenshot für die Diagnose von VM-Status anzeigen.
            &lt;Brasilien&gt;&lt;Br&gt; für virtuelle Linux-Computer, können Sie einfach die Ausgabe des Protokolls Konsole anzeigen. &lt;Brasilien&gt;&lt;Br&gt; für Windows- und Linux-VMs Azure können Sie auch einen Screenshot des virtuellen Computers von der Hypervisor anzuzeigen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.BootDiagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BootDiagnostics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnostics (Nullable&lt;bool&gt; enabled = null, string storageUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, string storageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.BootDiagnostics.#ctor(System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional storageUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.BootDiagnostics : Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.BootDiagnostics" Usage="new Microsoft.Azure.Management.Compute.Models.BootDiagnostics (enabled, storageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled">Gibt an, ob startdiagnoseeinstellungen auf dem virtuellen Computer aktiviert werden soll.</param>
        <param name="storageUri">URI des Speicherkontos an, der für die Platzierung der Konsolenausgabe und Screenshot verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der BootDiagnostics-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.BootDiagnostics.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.BootDiagnostics.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob startdiagnoseeinstellungen auf dem virtuellen Computer aktiviert werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public string StorageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.BootDiagnostics.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageUri As String" />
      <MemberSignature Language="F#" Value="member this.StorageUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.BootDiagnostics.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Uri des Speicherkontos zum Platzieren der Konsolenausgabe und Screenshot verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>