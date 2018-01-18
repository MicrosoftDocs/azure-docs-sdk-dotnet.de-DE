<Type Name="ActorTypeExtensions" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions">
  <TypeSignature Language="C#" Value="public static class ActorTypeExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorTypeExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActorTypeExtensions" />
  <TypeSignature Language="F#" Value="type ActorTypeExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a799b-101">Enthält die Erweiterungsmethode für Akteur-Typen.</span><span class="sxs-lookup"><span data-stu-id="a799b-101">Contains extension method for Actor types.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorEventInterfaces">
      <MemberSignature Language="C#" Value="public static Type[] GetActorEventInterfaces (this Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Type[] GetActorEventInterfaces(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorEventInterfaces(System.Type)" />
      <MemberSignature Language="F#" Value="static member GetActorEventInterfaces : Type -&gt; Type[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorEventInterfaces type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="a799b-102">Der Typ der Klasse implementierende Akteur.</span><span class="sxs-lookup"><span data-stu-id="a799b-102">The type of class implementing actor.</span></span></param>
        <summary>
            <span data-ttu-id="a799b-103">Ruft die Ereignisschnittstellen Akteur von der Akteurklasse implementiert.</span><span class="sxs-lookup"><span data-stu-id="a799b-103">Gets the actor event interfaces implemented by the actor class.</span></span>
            </summary>
        <returns><span data-ttu-id="a799b-104">Ein Array mit Akteur Ereignisschnittstelle, die der Typ implementiert.</span><span class="sxs-lookup"><span data-stu-id="a799b-104">An array containing actor event interface which the type implements.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActorInterfaces">
      <MemberSignature Language="C#" Value="public static Type[] GetActorInterfaces (this Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Type[] GetActorInterfaces(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorInterfaces(System.Type)" />
      <MemberSignature Language="F#" Value="static member GetActorInterfaces : Type -&gt; Type[]" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.GetActorInterfaces type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="a799b-105">Der Typ der Klasse implementierende Akteur.</span><span class="sxs-lookup"><span data-stu-id="a799b-105">The type of class implementing actor.</span></span></param>
        <summary>
            <span data-ttu-id="a799b-106">Ruft die Akteur-Schnittstellen, die von der Akteurklasse implementiert.</span><span class="sxs-lookup"><span data-stu-id="a799b-106">Gets the actor interfaces implemented by the actor class.</span></span>
            </summary>
        <returns><span data-ttu-id="a799b-107">Ein Array mit Akteur-Schnittstelle, die der Typ implementiert.</span><span class="sxs-lookup"><span data-stu-id="a799b-107">An array containing actor interface which the type implements.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActor">
      <MemberSignature Language="C#" Value="public static bool IsActor (this Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsActor(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActor(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsActor (actorType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsActor : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActor actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorType"><span data-ttu-id="a799b-108">Der Typ implementierende Akteur.</span><span class="sxs-lookup"><span data-stu-id="a799b-108">The type implementing actor.</span></span></param>
        <summary>
            <span data-ttu-id="a799b-109">Gibt einen Wert an, ob die ActorType Akteur ist.</span><span class="sxs-lookup"><span data-stu-id="a799b-109">Indicates a value whether the actorType is an actor.</span></span>
            </summary>
        <returns><span data-ttu-id="a799b-110">True, wenn die <see cref="P:System.Type.BaseType" /> ActorType ist ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="a799b-110">true, if the <see cref="P:System.Type.BaseType" /> of actorType is an <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActorInterface">
      <MemberSignature Language="C#" Value="public static bool IsActorInterface (this Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsActorInterface(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActorInterface(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsActorInterface (actorInterfaceType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsActorInterface : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsActorInterface actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="a799b-111">Der Schnittstellentyp des Darstellers.</span><span class="sxs-lookup"><span data-stu-id="a799b-111">The interface type of the actor.</span></span></param>
        <summary>
            <span data-ttu-id="a799b-112">Gibt an, ob der Schnittstellentyp ein Akteur-Schnittstelle ist.</span><span class="sxs-lookup"><span data-stu-id="a799b-112">Indicates whether the interface type is an actor interface.</span></span>
            </summary>
        <returns><span data-ttu-id="a799b-113">"true", wenn die ActorInterfaceType eine Schnittstelle ist nur implementiert <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> oder (<see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und <see cref="T:Microsoft.ServiceFabric.Actors.IActorEventPublisher" />), andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="a799b-113">true, if the actorInterfaceType is an interface only implements <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> or (<see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> and <see cref="T:Microsoft.ServiceFabric.Actors.IActorEventPublisher" />); otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRemindableActor">
      <MemberSignature Language="C#" Value="public static bool IsRemindableActor (this Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsRemindableActor(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsRemindableActor(System.Type)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsRemindableActor (actorType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsRemindableActor : Type -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeExtensions.IsRemindableActor actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actorType"><span data-ttu-id="a799b-114">Der Typ implementierende Akteur.</span><span class="sxs-lookup"><span data-stu-id="a799b-114">The type implementing actor.</span></span></param>
        <summary>
            <span data-ttu-id="a799b-115">Gibt einen Wert an, ob ein Akteurtyp implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="a799b-115">Indicates a value whether an actor type implements <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface.</span></span>
            </summary>
        <returns><span data-ttu-id="a799b-116">True, wenn die <paramref name="actorType" /> implementiert eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> -Schnittstelle, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="a799b-116">true, if the <paramref name="actorType" /> implements an <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>