<Type Name="NetworkSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings">
  <TypeSignature Language="C#" Value="public class NetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type NetworkSettings = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt die Netzwerkeinstellungen eines Geräts an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NetworkSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters, Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings webproxySettings, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters, class Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings webproxySettings, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList,Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList * Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings (dnsSettings, networkAdapters, webproxySettings, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings" />
        <Parameter Name="networkAdapters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList" />
        <Parameter Name="webproxySettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="dnsSettings">Die Einstellungen der DNS (Domain Name System) des Geräts.</param>
        <param name="networkAdapters">Die Netzwerk-Adapter-Liste des Geräts.</param>
        <param name="webproxySettings">Die Webproxy-Einstellungen des Geräts.</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <summary>
            Initialisiert eine neue Instanz der NetworkSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As DNSSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die DNS (Domain Name System)-Einstellungen des Geräts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAdapters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.NetworkAdapters" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAdapters As NetworkAdapterList" />
      <MemberSignature Language="F#" Value="member this.NetworkAdapters : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.NetworkAdapters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAdapters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Netzwerk-Adapter-Liste des Geräts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSettings.Validate " />
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
    <Member MemberName="WebproxySettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings WebproxySettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings WebproxySettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.WebproxySettings" />
      <MemberSignature Language="VB.NET" Value="Public Property WebproxySettings As WebproxySettings" />
      <MemberSignature Language="F#" Value="member this.WebproxySettings : Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.WebproxySettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webproxySettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Webproxy-Einstellungen des Geräts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>