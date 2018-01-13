<Type Name="OSDisk" FullName="Microsoft.Azure.Management.Compute.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
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
            Gibt Informationen zu den Betriebssystem-Datenträger, die von der virtuellen Maschine verwendet. &lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.#ctor" />
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
            Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings encryptionSettings = null, string name = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk vhd = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings encryptionSettings, string name, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk vhd, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes,System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings,System.String,Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional encryptionSettings As DiskEncryptionSettings = null, Optional name As String = null, Optional vhd As VirtualHardDisk = null, Optional image As VirtualHardDisk = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional managedDisk As ManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.OSDisk : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings * string * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Models.OSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.OSDisk (createOption, osType, encryptionSettings, name, vhd, image, caching, diskSizeGB, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vhd" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="createOption">Gibt an, wie die virtuelle Maschine erstellt werden sollen. &lt;Br&gt;&lt;Br&gt; folgende Werte sind möglich:&lt;Br&gt;&lt;Br&gt; **Anfügen** \u2013 dieser Wert verwendet wird, bei der Verwendung einer spezialisierten Datenträgers zum Erstellen des virtuellen Computers. &lt;Br&gt;&lt;Br&gt; **FromImage** \u2013 dieser Wert verwendet wird, wenn Sie ein Bild zum Erstellen des virtuellen Computers verwenden. Wenn Sie ein Plattformimage verwenden, verwenden Sie ebenfalls das oben beschriebene ImageReference-Element. Wenn Sie einem Marketplace-Image verwenden, verwenden Sie auch das Plan-Element, das zuvor beschrieben. Folgende Werte sind möglich: "FromImage", "Leer", "Anfügen"</param>
        <param name="osType">Diese Eigenschaft können Sie den Typ des Betriebssystems angeben, die auf dem Datenträger enthalten ist, wenn das Erstellen eines virtuellen Computers aus Benutzer-Image oder eine spezialisierte VHD. &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; **Windows** &lt;Br&gt; &lt;Br&gt; **Linux**. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <param name="encryptionSettings">Gibt die Einstellungen für die Verschlüsselung für den Betriebssystem-Datenträger an. &lt;Brasilien&gt;&lt;Br&gt; -api-Mindestversion: 2015-06-15</param>
        <param name="name">Der Name des Datenträgers.</param>
        <param name="vhd">Die virtuelle Festplatte.</param>
        <param name="image">Quellbenutzer Bild virtuelle Festplatte an. Die virtuelle Festplatte wird vor dem Anfügen an den virtuellen Computer kopiert werden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Festplatte für Ziel nicht vorhanden.</param>
        <param name="caching">Gibt die cacheanforderungen an.
            &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; **keine** &lt;Br&gt; &lt; Brasilien&gt; **ReadOnly** &lt;Br&gt;&lt;Br&gt; **ReadWrite** &lt;Br&gt; &lt;Br&gt; Default: **None für Standard-Speicher. ReadOnly für Premium-Speicher**. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</param>
        <param name="diskSizeGB">Gibt die Größe der einen leeren Datenträger in Gigabyte an. Dieses Element kann verwendet werden, um den Namen des Datenträgers in Abbild eines virtuellen Computers zu überschreiben. &lt;Brasilien&gt;&lt;Br&gt; dieser Wert darf nicht größer als 1023 GB sein</param>
        <param name="managedDisk">Die verwaltete Datenträgerparameter.</param>
        <summary>
            Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die cacheanforderungen an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Keine** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **ReadOnly** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **ReadWrite** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Standard: **None für Standard-Speicher. ReadOnly für Premium-Speicher**. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, wie die virtuelle Maschine erstellt werden sollen, ruft ab oder legt ihn fest. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind:&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Anfügen** \u2013 dieser Wert verwendet wird, wenn Sie zum Erstellen des virtuellen Computers ein speziellen Datenträgers verwenden.&amp; Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **FromImage** \u2013 dieser Wert verwendet wird, wenn Sie ein Bild zum Erstellen des virtuellen Computers verwenden. Wenn Sie ein Plattformimage verwenden, verwenden Sie ebenfalls das oben beschriebene ImageReference-Element. Wenn Sie einem Marketplace-Image verwenden, verwenden Sie auch das Plan-Element, das zuvor beschrieben. Folgende Werte sind möglich: "FromImage", "Leer", "Anfügen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt gibt die Größe der einen leeren Datenträger in Gigabyte an.
            Dieses Element kann verwendet werden, um den Namen des Datenträgers in Abbild eines virtuellen Computers zu überschreiben. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Dieser Wert darf nicht größer als 1023 GB sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As DiskEncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Einstellungen für die Verschlüsselung für den Betriebssystem-Datenträger an.
            &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Api-Mindestversion: 2015-06-15
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Benutzer Image virtuelle Quellfestplatte. Die virtuelle Festplatte wird vor dem Anfügen an den virtuellen Computer kopiert werden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Festplatte für Ziel nicht vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As ManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt können diese Eigenschaft zur Angabe des Betriebssystems, die auf dem Datenträger enthalten ist, wenn das Erstellen eines virtuellen Computers aus Benutzer-Image oder eine spezialisierte VHD. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Mögliche Werte sind: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Windows** &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; **Linux**. Folgende Werte sind möglich: "Windows", "Linux"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="oSDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Vhd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Vhd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Vhd" />
      <MemberSignature Language="VB.NET" Value="Public Property Vhd As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Vhd : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Vhd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualHardDisk</ReturnType>
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