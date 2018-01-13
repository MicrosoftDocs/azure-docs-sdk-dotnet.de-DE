<Type Name="CloudAppliance" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance">
  <TypeSignature Language="C#" Value="public class CloudAppliance" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudAppliance extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudAppliance" />
  <TypeSignature Language="F#" Value="type CloudAppliance = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Cloud-Anwendung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppliance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloudAppliance-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAppliance (string name, string vnetRegion, string vnetName = null, Nullable&lt;bool&gt; isVnetDnsConfigured = null, Nullable&lt;bool&gt; isVnetExpressConfigured = null, string subnetName = null, string storageAccountName = null, string storageAccountType = null, string vmType = null, string vmImageName = null, string modelNumber = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string vnetRegion, string vnetName, valuetype System.Nullable`1&lt;bool&gt; isVnetDnsConfigured, valuetype System.Nullable`1&lt;bool&gt; isVnetExpressConfigured, string subnetName, string storageAccountName, string storageAccountType, string vmType, string vmImageName, string modelNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, vnetRegion As String, Optional vnetName As String = null, Optional isVnetDnsConfigured As Nullable(Of Boolean) = null, Optional isVnetExpressConfigured As Nullable(Of Boolean) = null, Optional subnetName As String = null, Optional storageAccountName As String = null, Optional storageAccountType As String = null, Optional vmType As String = null, Optional vmImageName As String = null, Optional modelNumber As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance : string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance (name, vnetRegion, vnetName, isVnetDnsConfigured, isVnetExpressConfigured, subnetName, storageAccountName, storageAccountType, vmType, vmImageName, modelNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetRegion" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="isVnetDnsConfigured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isVnetExpressConfigured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="subnetName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="storageAccountType" Type="System.String" />
        <Parameter Name="vmType" Type="System.String" />
        <Parameter Name="vmImageName" Type="System.String" />
        <Parameter Name="modelNumber" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name.</param>
        <param name="vnetRegion">Die Region des virtuellen Netzwerks.</param>
        <param name="vnetName">Der Name des virtuellen Netzwerks.</param>
        <param name="isVnetDnsConfigured">Gibt an, ob verwendeten virtuellen Netzwerks mit DNS konfiguriert ist.</param>
        <param name="isVnetExpressConfigured">Gibt an, ob verwendeten virtuellen Netzwerks mit express-Route konfiguriert ist.</param>
        <param name="subnetName">Der Name des Subnetzes.</param>
        <param name="storageAccountName">Der Name des Speicherkontos.</param>
        <param name="storageAccountType">Der Typ des Speicherkontos.</param>
        <param name="vmType">Der Typ des virtuellen Computers.</param>
        <param name="vmImageName">Der Name des Image des virtuellen Computers.</param>
        <param name="modelNumber">Die Modellnummer.</param>
        <summary>
            Initialisiert eine neue Instanz der CloudAppliance-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsVnetDnsConfigured">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsVnetDnsConfigured { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsVnetDnsConfigured" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.IsVnetDnsConfigured" />
      <MemberSignature Language="VB.NET" Value="Public Property IsVnetDnsConfigured As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsVnetDnsConfigured : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.IsVnetDnsConfigured" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isVnetDnsConfigured")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei verwendeten virtuellen Netzwerks mit DNS konfiguriert ist, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsVnetExpressConfigured">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsVnetExpressConfigured { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsVnetExpressConfigured" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.IsVnetExpressConfigured" />
      <MemberSignature Language="VB.NET" Value="Public Property IsVnetExpressConfigured As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsVnetExpressConfigured : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.IsVnetExpressConfigured" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isVnetExpressConfigured")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob es sich bei verwendeten virtuellen Netzwerks mit express-Route konfiguriert ist, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModelNumber">
      <MemberSignature Language="C#" Value="public string ModelNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.ModelNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelNumber As String" />
      <MemberSignature Language="F#" Value="member this.ModelNumber : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.ModelNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="modelNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Modellnummer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft den Namen ab oder legt diesen fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountName">
      <MemberSignature Language="C#" Value="public string StorageAccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.StorageAccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountName As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.StorageAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public string StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetName">
      <MemberSignature Language="C#" Value="public string SubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.SubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetName As String" />
      <MemberSignature Language="F#" Value="member this.SubnetName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.SubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Subnetzes.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudAppliance.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="VmImageName">
      <MemberSignature Language="C#" Value="public string VmImageName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmImageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VmImageName" />
      <MemberSignature Language="VB.NET" Value="Public Property VmImageName As String" />
      <MemberSignature Language="F#" Value="member this.VmImageName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VmImageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmImageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Image des virtuellen Computers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmType">
      <MemberSignature Language="C#" Value="public string VmType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VmType" />
      <MemberSignature Language="VB.NET" Value="Public Property VmType As String" />
      <MemberSignature Language="F#" Value="member this.VmType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VmType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des virtuellen Computers fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des virtuellen Netzwerks.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetRegion">
      <MemberSignature Language="C#" Value="public string VnetRegion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VnetRegion" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetRegion As String" />
      <MemberSignature Language="F#" Value="member this.VnetRegion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.CloudAppliance.VnetRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vnetRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Region des virtuellen Netzwerks fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>