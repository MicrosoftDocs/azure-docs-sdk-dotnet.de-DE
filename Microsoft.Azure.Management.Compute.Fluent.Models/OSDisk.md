<Type Name="OSDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt die Betriebssystem-Datenträger.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public OSDisk (Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings encryptionSettings = null, string name = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk vhd = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings encryptionSettings, string name, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk vhd, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional encryptionSettings As DiskEncryptionSettings = null, Optional name As String = null, Optional vhd As VirtualHardDisk = null, Optional image As VirtualHardDisk = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional managedDisk As ManagedDiskParametersInner = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk (createOption, osType, encryptionSettings, name, vhd, image, caching, diskSizeGB, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vhd" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner" />
      </Parameters>
      <Docs>
        <param name="createOption">Die Create-Datenbankoption. Folgende Werte sind möglich: "FromImage", "empty", "Anfügen"</param>
        <param name="osType">Der Typ des Betriebssystems. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <param name="encryptionSettings">Die datenträgereinstellungen für die Verschlüsselung.</param>
        <param name="name">Der Name des Datenträgers.</param>
        <param name="vhd">Die virtuelle Festplatte.</param>
        <param name="image">Quellbenutzer Bild virtuelle Festplatte an. Die virtuelle Festplatte wird vor der Verwendung für die Verbindung mit dem virtuellen Computer kopiert werden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Zielfestplatte nicht vorhanden.</param>
        <param name="caching">Der caching-Typ. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</param>
        <param name="diskSizeGB">Die ursprüngliche Datenträgergröße, in GB für leere Datenträger, und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Betriebssystem und die Datenträger.</param>
        <param name="managedDisk">Die verwaltete Datenträgerparameter.</param>
        <summary>
            Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den caching-Typ. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die Option erstellen. Folgende Werte sind möglich: "FromImage", "empty", "Anfügen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, die ursprüngliche Datenträgergröße, in GB für leere Datenträger, und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Betriebssystem und die Datenträger.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As DiskEncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Datenträgers verschlüsselungseinstellungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Benutzer Image virtuelle Quellfestplatte. Die virtuelle Festplatte wird vor der Verwendung für die Verbindung mit dem virtuellen Computer kopiert werden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Zielfestplatte nicht vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As ManagedDiskParametersInner" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den verwalteten Datenträgerparameter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Datenträgernamen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Betriebssystemtyp. Folgende Werte sind möglich: "Windows", "Linux"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="oSDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Vhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Vhd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Vhd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Vhd" />
      <MemberSignature Language="VB.NET" Value="Public Property Vhd As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Vhd : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.OSDisk.Vhd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die virtuelle Festplatte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>