<Type Name="VirtualMachineScaleSetOSDisk" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetOSDisk = class" />
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
            Beschreibt die Betriebssystem-Datenträger eines virtuellen Computers Skala festlegen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.#ctor" />
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
            Initialisiert eine neue Instanz der VirtualMachineScaleSetOSDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk (Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, string name = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image = null, System.Collections.Generic.IList&lt;string&gt; vhdContainers = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image, class System.Collections.Generic.IList`1&lt;string&gt; vhdContainers, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional name As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional image As VirtualHardDisk = null, Optional vhdContainers As IList(Of String) = null, Optional managedDisk As VirtualMachineScaleSetManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk (createOption, name, caching, osType, image, vhdContainers, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="vhdContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="createOption">Gibt an, wie die virtuellen Computer in scaleset erstellt werden sollen. &lt;Br&gt;&lt;Br&gt; der einzige zulässige Wert lautet: **FromImage** \u2013 dieser Wert verwendet wird, wenn Sie ein Bild zum Erstellen des virtuellen Computers verwenden. Wenn Sie ein Plattformimage verwenden, verwenden Sie ebenfalls das oben beschriebene ImageReference-Element. Wenn Sie einem Marketplace-Image verwenden, verwenden Sie auch das Plan-Element, das zuvor beschrieben. Folgende Werte sind möglich: "FromImage", "Leer", "Anfügen"</param>
        <param name="name">Der Name des Datenträgers.</param>
        <param name="caching">Gibt die cacheanforderungen an.
            &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; **keine** &lt;Br&gt; &lt; Brasilien&gt; **ReadOnly** &lt;Br&gt;&lt;Br&gt; **ReadWrite** &lt;Br&gt; &lt;Br&gt; Default: **None für Standard-Speicher. ReadOnly für Premium-Speicher**. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</param>
        <param name="osType">Diese Eigenschaft können Sie den Typ des Betriebssystems angeben, die auf dem Datenträger enthalten ist, wenn das Erstellen eines virtuellen Computers aus Benutzer-Image oder eine spezialisierte VHD. &lt;Brasilien&gt;&lt;Br&gt; folgende Werte sind möglich: &lt;Br&gt;&lt;Br&gt; **Windows** &lt;Br&gt; &lt;Br&gt; **Linux**. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <param name="image">Gibt Informationen zu den nicht verwalteten benutzerimage das Scale set auf basieren.</param>
        <param name="vhdContainers">Gibt an, die Container-Urls, die zum Speichern von Betriebssystem-Datenträger für den Scale-Satz verwendet werden.</param>
        <param name="managedDisk">Die verwaltete Datenträgerparameter.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetOSDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Caching" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
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
            Gibt an, wie die virtuellen Computer in scaleset erstellt werden sollen, ruft ab oder legt ihn fest. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Der einzige zulässige Wert lautet: **FromImage** \u2013 dieser Wert verwendet wird, wenn Sie ein Bild zum Erstellen des virtuellen Computers verwenden. Wenn Sie ein Plattformimage verwenden, verwenden Sie ebenfalls das oben beschriebene ImageReference-Element. Wenn Sie einem Marketplace-Image verwenden, verwenden Sie auch das Plan-Element, das zuvor beschrieben. Folgende Werte sind möglich: "FromImage", "Leer", "Anfügen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Image" />
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
            Ruft ab oder legt gibt Informationen zu den nicht verwalteten benutzerimage das Scale set auf basieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As VirtualMachineScaleSetManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Name" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.OsType" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetOSDisk.Validate " />
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
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VhdContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhdContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Container-Urls, die zum Speichern von Betriebssystem-Datenträger für den Scale-Satz verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>