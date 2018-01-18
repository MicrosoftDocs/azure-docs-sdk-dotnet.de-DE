<Type Name="ActorStateChange" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange">
  <TypeSignature Language="C#" Value="public sealed class ActorStateChange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorStateChange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorStateChange" />
  <TypeSignature Language="F#" Value="type ActorStateChange = class" />
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
            <span data-ttu-id="6b069-101">Stellt eine Änderung in einem Akteur Zustand mit einem angegebenen Zustand "-Namen dar.</span><span class="sxs-lookup"><span data-stu-id="6b069-101">Represents a change to an actor state with a given state name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorStateChange (string stateName, Type type, object value, Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind changeKind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string stateName, class System.Type type, object value, valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind changeKind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.#ctor(System.String,System.Type,System.Object,Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange : string * Type * obj * Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange" Usage="new Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange (stateName, type, value, changeKind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="type" Type="System.Type" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="changeKind" Type="Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="6b069-102">Der Name des Zustands Akteur.</span><span class="sxs-lookup"><span data-stu-id="6b069-102">The name of the actor state.</span></span></param>
        <param name="type"><span data-ttu-id="6b069-103">Der Typ des Werts angegebene Akteur Statusname zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6b069-103">The type of value associated with given actor state name.</span></span></param>
        <param name="value"><span data-ttu-id="6b069-104">Der Wert, der angegebenen Akteur Zustand zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="6b069-104">The value associated with given actor state name.</span></span></param>
        <param name="changeKind"><span data-ttu-id="6b069-105">Die Art von Status ändern Akteur State Name.</span><span class="sxs-lookup"><span data-stu-id="6b069-105">The kind of state change for given actor state name.</span></span></param>
        <summary>
            <span data-ttu-id="6b069-106">Erstellt eine Instanz der ActorStateChange-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6b069-106">Creates an instance of ActorStateChange class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeKind">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind ChangeKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind ChangeKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.ChangeKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ChangeKind As StateChangeKind" />
      <MemberSignature Language="F#" Value="member this.ChangeKind : Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.ChangeKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b069-107">Ruft die Art von Status für die angegebene Akteur Statusname ändern werden.</span><span class="sxs-lookup"><span data-stu-id="6b069-107">Gets the kind of state change for given actor state name.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6b069-108">Die Art von Status ändern Akteur State Name.</span><span class="sxs-lookup"><span data-stu-id="6b069-108">The kind of state change for given actor state name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateName">
      <MemberSignature Language="C#" Value="public string StateName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StateName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.StateName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateName As String" />
      <MemberSignature Language="F#" Value="member this.StateName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.StateName" />
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
            <span data-ttu-id="6b069-109">Ruft den Namen des Akteurs Status ab.</span><span class="sxs-lookup"><span data-stu-id="6b069-109">Gets the name of the actor state.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6b069-110">Der Name des Zustands Akteur.</span><span class="sxs-lookup"><span data-stu-id="6b069-110">The name of the actor state.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Type Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As Type" />
      <MemberSignature Language="F#" Value="member this.Type : Type" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b069-111">Ruft den Typ des Werts angegebene Akteur Statusname zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6b069-111">Gets the type of value associated with given actor state name.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6b069-112">Der Typ des Werts angegebene Akteur Statusname zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6b069-112">The type of value associated with given actor state name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b069-113">Ruft den Wert mit dem angegebenen Akteur Zustand zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6b069-113">Gets the value associated with given actor state name.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6b069-114">Der Wert, der angegebenen Akteur Zustand zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="6b069-114">The value associated with given actor state name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>