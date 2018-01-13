<Type Name="ClusterCodeVersionsResult" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult">
  <TypeSignature Language="C#" Value="public class ClusterCodeVersionsResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterCodeVersionsResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterCodeVersionsResult" />
  <TypeSignature Language="F#" Value="type ClusterCodeVersionsResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Das Ergebnis der ServiceFabric Runtime-Versionen
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCodeVersionsResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClusterCodeVersionsResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCodeVersionsResult (string id = null, string name = null, string type = null, string codeVersion = null, string supportExpiryUtc = null, string environment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string codeVersion, string supportExpiryUtc, string environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional codeVersion As String = null, Optional supportExpiryUtc As String = null, Optional environment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult (id, name, type, codeVersion, supportExpiryUtc, environment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="supportExpiryUtc" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die Kennung des Ergebnisses</param>
        <param name="name">Der Name des Ergebnisses</param>
        <param name="type">Der Ergebnistyp für die Ressource</param>
        <param name="codeVersion">Die Laufzeitversion ServiceFabric des Clusters</param>
        <param name="supportExpiryUtc">Ablauf der Unterstützung der version</param>
        <param name="environment">Cluster-Betriebssystem. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <summary>
            Initialisiert eine neue Instanz der ClusterCodeVersionsResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.CodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.codeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Laufzeitversion ServiceFabric des Clusters
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Environment">
      <MemberSignature Language="C#" Value="public string Environment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Environment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Environment" />
      <MemberSignature Language="VB.NET" Value="Public Property Environment As String" />
      <MemberSignature Language="F#" Value="member this.Environment : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Environment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Cluster-Betriebssystem. Folgende Werte sind möglich: "Windows", "Linux"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Kennung des Ergebnisses
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
            Ruft ab oder legt den Namen des Ergebnisses
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportExpiryUtc">
      <MemberSignature Language="C#" Value="public string SupportExpiryUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SupportExpiryUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.SupportExpiryUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportExpiryUtc As String" />
      <MemberSignature Language="F#" Value="member this.SupportExpiryUtc : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.SupportExpiryUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportExpiryUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Datum der Ablauf der Unterstützung der version
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterCodeVersionsResult.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest ergebnisressourcentyps eingeben
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>