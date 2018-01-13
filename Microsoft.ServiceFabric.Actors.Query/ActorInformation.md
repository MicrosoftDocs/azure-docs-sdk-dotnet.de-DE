<Type Name="ActorInformation" FullName="Microsoft.ServiceFabric.Actors.Query.ActorInformation">
  <TypeSignature Language="C#" Value="public sealed class ActorInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ActorInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Query.ActorInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorInformation" />
  <TypeSignature Language="F#" Value="type ActorInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ActorInformation", Namespace="urn:actors")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt die Informationen zu einem Akteur Akteur Abfrage Methodenaufruf zurückgegebene dar. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorInformation (Microsoft.ServiceFabric.Actors.ActorId actorId, bool isActive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.ActorId actorId, bool isActive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Query.ActorInformation.#ctor(Microsoft.ServiceFabric.Actors.ActorId,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Query.ActorInformation : Microsoft.ServiceFabric.Actors.ActorId * bool -&gt; Microsoft.ServiceFabric.Actors.Query.ActorInformation" Usage="new Microsoft.ServiceFabric.Actors.Query.ActorInformation (actorId, isActive)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="isActive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="actorId">Die ID des Akteurs.</param>
        <param name="isActive">Gibt an, ob der Akteur aktiv oder inaktiv ist.</param>
        <summary>
            Initialisiert eine neue Instanz der ActorInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.ActorInformation.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId" Usage="Microsoft.ServiceFabric.Actors.Query.ActorInformation.ActorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ActorId", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Akteur-ID für den Akteur ab.
            </summary>
        <value>Die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> für den Akteur.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActive">
      <MemberSignature Language="C#" Value="public bool IsActive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Query.ActorInformation.IsActive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsActive As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsActive : bool" Usage="Microsoft.ServiceFabric.Actors.Query.ActorInformation.IsActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="IsActive", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob der Akteur aktiv ist.
            </summary>
        <value>
          <see cref="T:System.Boolean" />der angibt, ob der Akteur aktiv ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>