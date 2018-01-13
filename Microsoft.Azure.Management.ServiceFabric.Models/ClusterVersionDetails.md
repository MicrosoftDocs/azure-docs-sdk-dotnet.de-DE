<Type Name="ClusterVersionDetails" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails">
  <TypeSignature Language="C#" Value="public class ClusterVersionDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterVersionDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterVersionDetails" />
  <TypeSignature Language="F#" Value="type ClusterVersionDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Details des Ergebnisses ServiceFabric Common Language Runtime-version
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterVersionDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClusterVersionDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterVersionDetails (string codeVersion = null, string supportExpiryUtc = null, string environment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string codeVersion, string supportExpiryUtc, string environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional codeVersion As String = null, Optional supportExpiryUtc As String = null, Optional environment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails : string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails (codeVersion, supportExpiryUtc, environment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="supportExpiryUtc" Type="System.String" />
        <Parameter Name="environment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersion">Die Laufzeitversion ServiceFabric des Clusters</param>
        <param name="supportExpiryUtc">Ablauf der Unterstützung der version</param>
        <param name="environment">Cluster-Betriebssystem. Folgende Werte sind möglich: "Windows", "Linux"</param>
        <summary>
            Initialisiert eine neue Instanz der ClusterVersionDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.CodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="codeVersion")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.Environment" />
      <MemberSignature Language="VB.NET" Value="Public Property Environment As String" />
      <MemberSignature Language="F#" Value="member this.Environment : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.Environment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environment")</AttributeName>
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
    <Member MemberName="SupportExpiryUtc">
      <MemberSignature Language="C#" Value="public string SupportExpiryUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SupportExpiryUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.SupportExpiryUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportExpiryUtc As String" />
      <MemberSignature Language="F#" Value="member this.SupportExpiryUtc : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails.SupportExpiryUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportExpiryUtc")</AttributeName>
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
  </Members>
</Type>