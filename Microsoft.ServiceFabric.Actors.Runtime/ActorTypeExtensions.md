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
            Enthält die Erweiterungsmethode für Akteur-Typen.
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
        <param name="type">Der Typ der Klasse implementierende Akteur.</param>
        <summary>
            Ruft die Ereignisschnittstellen Akteur von der Akteurklasse implementiert.
            </summary>
        <returns>Ein Array mit Akteur Ereignisschnittstelle, die der Typ implementiert.</returns>
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
        <param name="type">Der Typ der Klasse implementierende Akteur.</param>
        <summary>
            Ruft die Akteur-Schnittstellen, die von der Akteurklasse implementiert.
            </summary>
        <returns>Ein Array mit Akteur-Schnittstelle, die der Typ implementiert.</returns>
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
        <param name="actorType">Der Typ implementierende Akteur.</param>
        <summary>
            Gibt einen Wert an, ob die ActorType Akteur ist.
            </summary>
        <returns>True, wenn die <see cref="P:System.Type.BaseType" /> ActorType ist ein <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />, andernfalls "false".</returns>
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
        <param name="actorInterfaceType">Der Schnittstellentyp des Darstellers.</param>
        <summary>
            Gibt an, ob der Schnittstellentyp ein Akteur-Schnittstelle ist.
            </summary>
        <returns>"true", wenn die ActorInterfaceType eine Schnittstelle ist nur implementiert <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> oder (<see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und <see cref="T:Microsoft.ServiceFabric.Actors.IActorEventPublisher" />), andernfalls "false".</returns>
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
        <param name="actorType">Der Typ implementierende Akteur.</param>
        <summary>
            Gibt einen Wert an, ob ein Akteurtyp implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle.
            </summary>
        <returns>True, wenn die <paramref name="actorType" /> implementiert eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> -Schnittstelle, andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>