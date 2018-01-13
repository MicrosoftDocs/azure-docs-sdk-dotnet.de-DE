<Type Name="ReentrantActorInvalidStateException" FullName="Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException">
  <TypeSignature Language="C#" Value="public sealed class ReentrantActorInvalidStateException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReentrantActorInvalidStateException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReentrantActorInvalidStateException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type ReentrantActorInvalidStateException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0c29f-101">Ausnahme, die vom Akteur-Laufzeit ausgelöst, wenn die actorzustands während reeentrant-Aufruf ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="0c29f-101">Exception thrown by actor runtime if the actor state is invalid during reentrant call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0c29f-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0c29f-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException : string -&gt; Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" Usage="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="0c29f-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="0c29f-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="0c29f-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="0c29f-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" Usage="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="0c29f-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="0c29f-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="0c29f-106">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="0c29f-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="0c29f-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="0c29f-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>