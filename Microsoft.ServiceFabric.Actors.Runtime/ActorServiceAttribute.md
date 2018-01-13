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
            Stellt die Attribute, die ermöglicht das Konfigurieren der Eigenschaften des Diensts Akteurs dar. Das Attribut wird auf dem Akteurtyp angewendet.
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
            Initialisiert eine neue Instanz der ActorServiceAttribute-Klasse.
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
            Ruft ab oder legt den relativen Namen des Diensts Akteur. Dieser Name wird mit der Anwendungsname, geben Sie den vollständigen Namen des Diensts Akteur kombiniert werden. 
            </summary>
        <value>Der Name des Diensts Akteur relativ zu den Namen der Anwendung.</value>
        <remarks>
          <para>
                Standardmäßig ist der Dienstname Akteur vom Typ der Akteur-Schnittstelle abgeleitet (<see cref="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />). Allerdings für den Fall, dass wenn eine Akteur-Schnittstelle von mehr als ein Akteur implementiert wird, kann nicht von einem abgeleiteten Typ einschließlich, der Name werden von der Akteur-Schnittstelle eindeutig bestimmt. In diesem Fall der Namen des Diensts Akteur muss konfiguriert werden mit dieser Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.
                </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>