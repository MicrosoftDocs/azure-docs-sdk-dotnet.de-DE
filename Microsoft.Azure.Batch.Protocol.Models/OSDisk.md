<Type Name="OSDisk" FullName="Microsoft.Azure.Batch.Protocol.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
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
            Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OSDisk.#ctor" />
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
            Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OSDisk.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional caching As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OSDisk : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.OSDisk" Usage="new Microsoft.Azure.Batch.Protocol.Models.OSDisk caching" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="caching">Der Typ des Zwischenspeichern konfigurieren, um für den Betriebssystem-Datenträger zu aktivieren.</param>
        <summary>
            Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des caching zum Aktivieren der für den Betriebssystem-Datenträger.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert für das caching ist none. Weitere Informationen zu Optionen für die Zwischenspeicherung finden Sie unter: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.
            Folgende Werte sind möglich: "none", "ReadOnly", "ReadWrite"
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>