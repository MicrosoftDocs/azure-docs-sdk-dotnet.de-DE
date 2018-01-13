<Type Name="ActorTypeInformation" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation">
  <TypeSignature Language="C#" Value="public sealed class ActorTypeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorTypeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorTypeInformation" />
  <TypeSignature Language="F#" Value="type ActorTypeInformation = class" />
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
            Enthält Informationen über den Typ, der einen Akteur implementieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorTypeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ActorTypeInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventInterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; EventInterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; EventInterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventInterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.EventInterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Akteur Ereignisschnittstelle, die die Akteurklasse implementiert.
            </summary>
        <value>Ein Enumerator, der verwendet werden kann, durchlaufen über Ereignisschnittstelle Akteur die die Akteurklasse implementiert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get (Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Get (actorType As Type) As ActorTypeInformation" />
      <MemberSignature Language="F#" Value="static member Get : Type -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorType">Der Typ der Klasse, die den Akteur zum Erstellen von ActorTypeInforamtion für implementiert.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> aus ActorType.
            </summary>
        <returns>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />aus ActorType erstellt wurden.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Wenn <see cref="P:System.Type.BaseType" /> für ActorType nicht vom Typ ist <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</para>
          <para>Wenn ActorType keine Schnittstelle ableiten von implementiert <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und ist nicht als abstrakt gekennzeichnet.</para>
          <para>Wenn ActorType implementiert mehrere Schnittstellen abgeleitet von <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> jedoch keine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ImplementationType">
      <MemberSignature Language="C#" Value="public Type ImplementationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ImplementationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImplementationType As Type" />
      <MemberSignature Language="F#" Value="member this.ImplementationType : Type" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
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
            Ruft den Typ der Klasse, die den Akteur implementieren.
            </summary>
        <value>Die <see cref="T:System.Type" /> der Implementierung des Akteurs-Klasse.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; InterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; InterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.InterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Akteur Schnittstellentypen die Ableitung <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und vom Akteurklasse implementiert werden.
            </summary>
        <value>Ein Enumerator, der zum Durchlaufen des Akteur Schnittstellentyps verwendet werden kann.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAbstract">
      <MemberSignature Language="C#" Value="public bool IsAbstract { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAbstract" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAbstract As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAbstract : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, ob die implementierende Klasse Akteur abstrakt ist.
            </summary>
        <value>"true", wenn die implementierende Klasse Akteur abstrakt, andernfalls "false ist".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRemindable">
      <MemberSignature Language="C#" Value="public bool IsRemindable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRemindable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRemindable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRemindable : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, ob die Akteurklasse implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />.
            </summary>
        <value>"true", wenn die Akteurklasse implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />, andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
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
            Ruft den Dienstnamen ab, falls angegeben, mit <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> für Akteurklasse.
            </summary>
        <value>Der Dienstname angegeben mit <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> für Akteurklasse, null, wenn das Attribut nicht verwendet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePersistence">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatePersistence As StatePersistence" />
      <MemberSignature Language="F#" Value="member this.StatePersistence : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> Enum-Typ von Statuspersistenz für den Akteur darstellt.
            </summary>
        <value>Die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> , der Typ des Sitzungszustands für der Akteur darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public static bool TryGet (Type actorType, out Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGet(class System.Type actorType, [out] class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp; actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet(System.Type,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGet (actorType As Type, ByRef actorTypeInformation As ActorTypeInformation) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGet : Type *  -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet (actorType, actorTypeInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="actorType">Der Typ der Klasse, die den Akteur zum Erstellen von ActorTypeInforamtion für implementiert.</param>
        <param name="actorTypeInformation">Diese Methode zurückgibt, enthält ActorTypeInformation, wenn die Erstellung von ActorTypeInformation aus ActorType erfolgreich war, oder Null, wenn Fehler beim Erstellen.
            Die Erstellung schlägt fehl, wenn der ActorType-Parameter null ist oder einen Akteur wird nicht implementiert.</param>
        <summary>
            Erstellt die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> aus ActorType.
            </summary>
        <returns>"true", wenn ActorTypeInformation für ActorType erfolgreich erstellt wurde; andernfalls "false".</returns>
        <remarks>
          <para>Erstellung von ActorTypeInformation aus ActorType fehl, wenn </para>
          <para>1. <see cref="P:System.Type.BaseType" />für ActorType nicht vom Typ ist <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</para>
          <para>2. ActorType implementiert eine Schnittstelle ableiten von nicht <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und ist nicht als abstrakt gekennzeichnet.</para>
          <para>3. ActorType implementiert mehrere Schnittstellen abgeleitet von <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> jedoch keine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>