<Type Name="ConnectivityDestination" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityDestination">
  <TypeSignature Language="C#" Value="public class ConnectivityDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityDestination" />
  <TypeSignature Language="F#" Value="type ConnectivityDestination = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter, die Ziel der Verbindung zu definieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityDestination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ConnectivityDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityDestination (string resourceId = null, string address = null, Nullable&lt;int&gt; port = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceId, string address, valuetype System.Nullable`1&lt;int32&gt; port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityDestination.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceId As String = null, Optional address As String = null, Optional port As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityDestination : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityDestination" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityDestination (resourceId, address, port)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceId">Die ID der Ressource, auf die ein Verbindungsversuch vorgenommen wird.</param>
        <param name="address">Die IP-Adresse oder den URI erfolgt die Ressource, der eine Verbindung herzustellen.</param>
        <param name="port">Port für die Überprüfung der Konnektivität ausgeführt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ConnectivityDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityDestination.Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityDestination.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Adresse oder den URI die Ressource, an der ein Verbindungsversuch vorgenommen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityDestination.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityDestination.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Port, für welche Prüfung Konnektivität ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityDestination.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityDestination.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID der Ressource, auf die ein Verbindungsversuch vorgenommen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>