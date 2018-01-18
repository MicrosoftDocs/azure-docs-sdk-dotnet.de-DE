<Type Name="ActorServiceAttribute" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type ActorServiceAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0a7b6-101">Stellt die Attribute, die ermöglicht das Konfigurieren der Eigenschaften des Diensts Akteurs dar.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-101">Represents the attributes that allows configuring the properties of the actor service.</span></span> <span data-ttu-id="0a7b6-102">Das Attribut wird auf dem Akteurtyp angewendet.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-102">The attribute is applied on the actor type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a7b6-103">Initialisiert eine neue Instanz der ActorServiceAttribute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-103">Initializes a new instance of the ActorServiceAttribute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a7b6-104">Ruft ab oder legt den relativen Namen des Diensts Akteur.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-104">Gets or sets the relative name of the actor service.</span></span> <span data-ttu-id="0a7b6-105">Dieser Name wird mit der Anwendungsname, geben Sie den vollständigen Namen des Diensts Akteur kombiniert werden.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-105">This name will be combined with the application name to provide the full name of the actor service.</span></span> 
            </summary>
        <value><span data-ttu-id="0a7b6-106">Der Name des Diensts Akteur relativ zu den Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-106">The name of the actor service relative to the application name.</span></span></value>
        <remarks>
          <para>
                <span data-ttu-id="0a7b6-107">Standardmäßig ist der Dienstname Akteur vom Typ der Akteur-Schnittstelle abgeleitet (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />).</span><span class="sxs-lookup"><span data-stu-id="0a7b6-107">By default, the actor service name is derived from the type of the actor interface (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />).</span></span> <span data-ttu-id="0a7b6-108">Allerdings für den Fall, dass wenn eine Akteur-Schnittstelle von mehr als ein Akteur implementiert wird, kann nicht von einem abgeleiteten Typ einschließlich, der Name werden von der Akteur-Schnittstelle eindeutig bestimmt.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-108">However, in case when an actor interface is implemented by more than one actor, including by a derived type, the name cannot be determined from the actor interface in an unambiguous manner.</span></span> <span data-ttu-id="0a7b6-109">In diesem Fall der Namen des Diensts Akteur muss konfiguriert werden mit dieser Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span><span class="sxs-lookup"><span data-stu-id="0a7b6-109">In that case, the name of the actor service must be configured using this property of the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span></span>
                </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>