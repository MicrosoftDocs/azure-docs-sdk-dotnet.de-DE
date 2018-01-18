<Type Name="UserIdentity" FullName="Microsoft.Azure.Batch.Protocol.Models.UserIdentity">
  <TypeSignature Language="C#" Value="public class UserIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class UserIdentity" />
  <TypeSignature Language="F#" Value="type UserIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ffbb5-101">Die Definition der Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-101">The definition of the user identity under which the task is run.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="ffbb5-102">Geben Sie den Benutzernamen oder AutoUser-Eigenschaft, aber nicht beides.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-102">Specify either the userName or autoUser property, but not both.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UserIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ffbb5-103">Initialisiert eine neue Instanz der Klasse UserIdentity an.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-103">Initializes a new instance of the UserIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (string userName = null, Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification autoUser = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, class Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification autoUser) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UserIdentity.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional userName As String = null, Optional autoUser As AutoUserSpecification = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.UserIdentity : string * Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.UserIdentity" Usage="new Microsoft.Azure.Batch.Protocol.Models.UserIdentity (userName, autoUser)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="autoUser" Type="Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="ffbb5-104">Der Name der Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-104">The name of the user identity under which the task is run.</span></span></param>
        <param name="autoUser"><span data-ttu-id="ffbb5-105">Der Auto-Benutzer, unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-105">The auto user under which the task is run.</span></span></param>
        <summary>
            <span data-ttu-id="ffbb5-106">Initialisiert eine neue Instanz der Klasse UserIdentity an.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-106">Initializes a new instance of the UserIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification AutoUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification AutoUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserIdentity.AutoUser" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUser As AutoUserSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoUser : Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserIdentity.AutoUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoUser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoUserSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ffbb5-107">Abrufen oder festlegen den automatischen Benutzer unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-107">Gets or sets the auto user under which the task is run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ffbb5-108">Die Eigenschaften "UserName" und "AutoUser schließen sich gegenseitig aus; Sie müssen eine angeben, aber nicht beides.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-108">The userName and autoUser properties are mutually exclusive; you must specify one but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UserIdentity.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UserIdentity.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ffbb5-109">Ruft ab oder legt den Namen der Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-109">Gets or sets the name of the user identity under which the task is run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ffbb5-110">Die Eigenschaften "UserName" und "AutoUser schließen sich gegenseitig aus; Sie müssen eine angeben, aber nicht beides.</span><span class="sxs-lookup"><span data-stu-id="ffbb5-110">The userName and autoUser properties are mutually exclusive; you must specify one but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>