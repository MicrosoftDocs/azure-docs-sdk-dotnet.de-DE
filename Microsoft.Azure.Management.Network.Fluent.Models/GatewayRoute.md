<Type Name="GatewayRoute" FullName="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute">
  <TypeSignature Language="C#" Value="public class GatewayRoute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GatewayRoute extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute" />
  <TypeSignature Language="VB.NET" Value="Public Class GatewayRoute" />
  <TypeSignature Language="F#" Value="type GatewayRoute = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GatewayRoute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der GatewayRoute-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GatewayRoute (string localAddress = null, string network = null, string nextHop = null, string sourcePeer = null, string origin = null, string asPath = null, Nullable&lt;int&gt; weight = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localAddress, string network, string nextHop, string sourcePeer, string origin, string asPath, valuetype System.Nullable`1&lt;int32&gt; weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional localAddress As String = null, Optional network As String = null, Optional nextHop As String = null, Optional sourcePeer As String = null, Optional origin As String = null, Optional asPath As String = null, Optional weight As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute : string * string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute (localAddress, network, nextHop, sourcePeer, origin, asPath, weight)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="localAddress" Type="System.String" />
        <Parameter Name="network" Type="System.String" />
        <Parameter Name="nextHop" Type="System.String" />
        <Parameter Name="sourcePeer" Type="System.String" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="asPath" Type="System.String" />
        <Parameter Name="weight" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="localAddress">Die lokale Gatewayadresse</param>
        <param name="network">Das Routenpräfix Netzwerk</param>
        <param name="nextHop">Nächsten Hops der route</param>
        <param name="sourcePeer">Der Peer wurde diese Route aus gelernt haben.</param>
        <param name="origin">Die Quelle wurde diese Route aus gelernt haben.</param>
        <param name="asPath">ALS Folge der Pfad der route</param>
        <param name="weight">Die Route-Gewichtung</param>
        <summary>
            Initialisiert eine neue Instanz der GatewayRoute-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsPath">
      <MemberSignature Language="C#" Value="public string AsPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AsPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.AsPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsPath As String" />
      <MemberSignature Language="F#" Value="member this.AsPath : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.AsPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="asPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Route als Pfad Sequenz ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalAddress">
      <MemberSignature Language="C#" Value="public string LocalAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.LocalAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalAddress : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.LocalAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die lokale Gatewayadresse
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Network">
      <MemberSignature Language="C#" Value="public string Network { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Network" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Network" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Network As String" />
      <MemberSignature Language="F#" Value="member this.Network : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Network" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="network")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Routenpräfix Netzwerk ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHop">
      <MemberSignature Language="C#" Value="public string NextHop { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHop" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.NextHop" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHop As String" />
      <MemberSignature Language="F#" Value="member this.NextHop : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.NextHop" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHop")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die nächsten Hops der Route ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Origin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Quelle, die, der diese Route aus gelernt wurde, ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePeer">
      <MemberSignature Language="C#" Value="public string SourcePeer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePeer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.SourcePeer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourcePeer As String" />
      <MemberSignature Language="F#" Value="member this.SourcePeer : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.SourcePeer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePeer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Peer, die, dem diese Route aus gelernt wurde
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Weight { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Weight" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Weight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.GatewayRoute.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Route-Gewichtung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>