<Type Name="UserIdentity" FullName="Microsoft.Azure.Batch.UserIdentity">
  <TypeSignature Language="C#" Value="public class UserIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UserIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class UserIdentity" />
  <TypeSignature Language="F#" Value="type UserIdentity = class&#xA;    interface ITransportObjectProvider&lt;UserIdentity&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="b08f2-101">Die Definition der Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b08f2-101">The definition of the user identity under which the task is run.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (Microsoft.Azure.Batch.AutoUserSpecification autoUserSpecification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.AutoUserSpecification autoUserSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserIdentity.#ctor(Microsoft.Azure.Batch.AutoUserSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserIdentity : Microsoft.Azure.Batch.AutoUserSpecification -&gt; Microsoft.Azure.Batch.UserIdentity" Usage="new Microsoft.Azure.Batch.UserIdentity autoUserSpecification" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoUserSpecification" Type="Microsoft.Azure.Batch.AutoUserSpecification" />
      </Parameters>
      <Docs>
        <param name="autoUserSpecification"><span data-ttu-id="b08f2-102">Der Auto-Benutzer, unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b08f2-102">The auto user under which the task is run.</span></span></param>
        <summary>
            <span data-ttu-id="b08f2-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.UserIdentity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b08f2-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.UserIdentity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserIdentity (string userName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserIdentity.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserIdentity : string -&gt; Microsoft.Azure.Batch.UserIdentity" Usage="new Microsoft.Azure.Batch.UserIdentity userName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="b08f2-104">Der Benutzername, der die Identität des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="b08f2-104">The user name of the user identity.</span></span></param>
        <summary>
            <span data-ttu-id="b08f2-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.UserIdentity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b08f2-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.UserIdentity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoUserSpecification AutoUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoUserSpecification AutoUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoUser As AutoUserSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoUser : Microsoft.Azure.Batch.AutoUserSpecification" Usage="Microsoft.Azure.Batch.UserIdentity.AutoUser" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoUserSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b08f2-106">Ruft den Auto-Benutzer, die unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b08f2-106">Gets the auto user under which the task is run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b08f2-107">Die <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" /> und <see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" /> Eigenschaften schließen sich gegenseitig; Sie müssen eine angeben, aber nicht beides.</span><span class="sxs-lookup"><span data-stu-id="b08f2-107">The <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" /> and <see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" /> properties are mutually exclusive; you must specify one but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserIdentity.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.Azure.Batch.UserIdentity.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b08f2-108">Ruft den Namen der Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b08f2-108">Gets the name of the user identity under which the task is run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b08f2-109">Die <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" /> und <see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" /> Eigenschaften schließen sich gegenseitig; Sie müssen eine angeben, aber nicht beides.</span><span class="sxs-lookup"><span data-stu-id="b08f2-109">The <see cref="P:Microsoft.Azure.Batch.UserIdentity.UserName" /> and <see cref="P:Microsoft.Azure.Batch.UserIdentity.AutoUser" /> properties are mutually exclusive; you must specify one but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>