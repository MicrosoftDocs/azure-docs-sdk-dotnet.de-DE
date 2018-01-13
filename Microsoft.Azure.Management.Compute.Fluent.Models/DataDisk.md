<Type Name="DataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class" />
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
            Beschreibt einen Datenträger an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk vhd = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk vhd, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.#ctor(System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, createOption As DiskCreateOptionTypes, Optional name As String = null, Optional vhd As VirtualHardDisk = null, Optional image As VirtualHardDisk = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional managedDisk As ManagedDiskParametersInner = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk : int * Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk (lun, createOption, name, vhd, image, caching, diskSizeGB, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vhd" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner" />
      </Parameters>
      <Docs>
        <param name="lun">Die logische Gerätenummer.</param>
        <param name="createOption">Die Create-Datenbankoption. Folgende Werte sind möglich: "FromImage", "empty", "Anfügen"</param>
        <param name="name">Der Name des Datenträgers.</param>
        <param name="vhd">Die virtuelle Festplatte.</param>
        <param name="image">Quellbenutzer Bild virtuelle Festplatte an. Diese virtuelle Festplatte wird kopiert werden, bevor Sie sie für die Verbindung mit dem virtuellen Computer verwenden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Zielfestplatte nicht vorhanden.</param>
        <param name="caching">Der caching-Typ. Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</param>
        <param name="diskSizeGB">Die anfängliche Festplattengröße in GB für leere Datenträger, und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Betriebssystem und die Datenträger.</param>
        <param name="managedDisk">Die verwaltete Datenträgerparameter.</param>
        <summary>
            Initialisiert eine neue Instanz der DataDisk-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Caching" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.CreateOption" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.DiskSizeGB" />
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
            Ruft ab oder legt die anfängliche Festplattengröße in GB für leere Datenträger und die neue gewünschte Größe für das Ändern der Größe von vorhandenen Betriebssystem und die Datenträger.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Image" />
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
            Abrufen oder Festlegen der Benutzer Image virtuelle Quellfestplatte. Diese virtuelle Festplatte wird kopiert werden, bevor Sie sie für die Verbindung mit dem virtuellen Computer verwenden. Wenn SourceImage bereitgestellt wird, muss die virtuelle Zielfestplatte nicht vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der logischen Einheit.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As ManagedDiskParametersInner" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Fluent.Models.ManagedDiskParametersInner with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.ManagedDisk" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Name" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisk.Validate " />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Vhd" />
      <MemberSignature Language="VB.NET" Value="Public Property Vhd As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Vhd : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDisk.Vhd" />
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