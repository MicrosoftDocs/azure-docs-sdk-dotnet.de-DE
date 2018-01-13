<Type Name="ConnectionDetail" FullName="Microsoft.ServiceBus.Management.ConnectionDetail">
  <TypeSignature Language="C#" Value="public class ConnectionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.ConnectionDetail" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionDetail" />
  <TypeSignature Language="F#" Value="type ConnectionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ConnectionDetail", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="3f09d-101">Stellt die Details der Servicebus-Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-101">Represents the details associated with the service bus connection.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.ConnectionDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationType">
      <MemberSignature Language="C#" Value="public string AuthorizationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.AuthorizationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationType : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.AuthorizationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="AuthorizationType", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3f09d-102">Ruft ab oder legt den Autorisierungstyp für die Verbindung fest.</span><span class="sxs-lookup"><span data-stu-id="3f09d-102">Gets or sets the authorization type for the connection.</span></span></summary>
        <value><span data-ttu-id="3f09d-103">Der Autorisierungstyp für die Verbindung.</span><span class="sxs-lookup"><span data-stu-id="3f09d-103">The authorization type for the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ConnectionString", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3f09d-104">Ruft ab oder legt die Verbindungszeichenfolge der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-104">Gets or sets the connection string associated with the connection.</span></span></summary>
        <value><span data-ttu-id="3f09d-105">Die Verbindungszeichenfolge der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-105">The connection string associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="KeyName", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3f09d-106">Ruft ab oder legt der Schlüsselname der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-106">Gets or sets the key name associated with the connection.</span></span></summary>
        <value><span data-ttu-id="3f09d-107">Der Schlüsselname der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-107">The key name associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IEnumerable(Of AccessRights)" />
      <MemberSignature Language="F#" Value="member this.Rights : seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Rights", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3f09d-108">Ruft ab oder legt die Zugriffsrechte, die der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-108">Gets or sets the access rights associated with the connection.</span></span></summary>
        <value><span data-ttu-id="3f09d-109">Die Zugriffsrechte der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-109">The access rights associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.ConnectionDetail.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string with get, set" Usage="Microsoft.ServiceBus.Management.ConnectionDetail.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SecondaryConnectionString", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3f09d-110">Ruft ab oder legt die sekundären Verbindungszeichenfolge der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-110">Gets or sets the secondary connection string associated with the connection.</span></span></summary>
        <value><span data-ttu-id="3f09d-111">Der sekundären Verbindungszeichenfolge der Verbindung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3f09d-111">The secondary connection string associated with the connection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>