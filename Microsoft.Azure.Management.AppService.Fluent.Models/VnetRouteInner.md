<Type Name="VnetRouteInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner">
  <TypeSignature Language="C#" Value="public class VnetRouteInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetRouteInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetRouteInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetRouteInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Virtuelles Netzwerk Route-Vertrag verwendet, um die Routinginformationen für ein virtuelles Netzwerk zu übergeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRouteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VnetRouteInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetRouteInner (string id = null, string name = null, string kind = null, string type = null, string vnetRouteName = null, string startAddress = null, string endAddress = null, string routeType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetRouteName, string startAddress, string endAddress, string routeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetRouteName As String = null, Optional startAddress As String = null, Optional endAddress As String = null, Optional routeType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner (id, name, kind, type, vnetRouteName, startAddress, endAddress, routeType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetRouteName" Type="System.String" />
        <Parameter Name="startAddress" Type="System.String" />
        <Parameter Name="endAddress" Type="System.String" />
        <Parameter Name="routeType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="vnetRouteName">To be added.</param>
        <param name="startAddress">To be added.</param>
        <param name="endAddress">To be added.</param>
        <param name="routeType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAddress">
      <MemberSignature Language="C#" Value="public string EndAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.EndAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.EndAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Endadresse für diese Route. Wenn die erste Adresse in CIDR-Notation angegeben wird, muss dies ausgelassen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteType">
      <MemberSignature Language="C#" Value="public string RouteType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.RouteType" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteType As String" />
      <MemberSignature Language="F#" Value="member this.RouteType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.RouteType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab oder legt den Typ der Route sieht: Standard – standardmäßig wird für jede app hat, leitet an die lokale Adressbereiche gemäß RFC1918 VERERBT - Routen von realen virtuelle Netzwerkrouten STATIC - statischen Routen, legen Sie für die app nur geerbt
             
             Diese Werte werden für die Synchronisierung von einer app-Routen, mit denen von einem virtuellen Netzwerk verwendet werden. Folgende Werte sind möglich: 'DEFAULT', "GEERBTE", "STATIC"
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAddress">
      <MemberSignature Language="C#" Value="public string StartAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.StartAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.StartAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startadresse für diese Route fest. Dies kann auch eine CIDR-Notation, umfassen, in der Fall die letzte Adresse nicht angegeben werden muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetRouteName">
      <MemberSignature Language="C#" Value="public string VnetRouteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetRouteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.VnetRouteName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetRouteName As String" />
      <MemberSignature Language="F#" Value="member this.VnetRouteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner.VnetRouteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen dieser Route. Dies wird nur zurückgegeben, durch den Server und muss nicht vom Client festgelegt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>