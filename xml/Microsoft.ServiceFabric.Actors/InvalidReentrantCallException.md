<Type Name="InvalidReentrantCallException" FullName="Microsoft.ServiceFabric.Actors.InvalidReentrantCallException">
  <TypeSignature Language="C#" Value="public sealed class InvalidReentrantCallException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit InvalidReentrantCallException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class InvalidReentrantCallException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type InvalidReentrantCallException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="c75ca-101">Diese Ausnahme wird vom Akteur-Laufzeit ausgelöst, wenn mehr als ein reeentrant-Aufruf-Kette, die zur gleichen Zeit für einen Akteur aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="c75ca-101">This exception is thrown by actor runtime when more than one reentrant call chain is active for an actor at the same time.</span></span>
            <span data-ttu-id="c75ca-102"><para>Dies kann geschehen Szenario, in dem Akteur A ruft Akteur B, C und D parallel und dann B, C und D aufrufen, ein gleichzeitig speichern.</para></span><span class="sxs-lookup"><span data-stu-id="c75ca-102"><para> This can happen in scenario where actor A calls actor B, C and D in parallel and then B, C and D try to call back A at the same time. </para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c75ca-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c75ca-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException : string -&gt; Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" Usage="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="c75ca-104">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="c75ca-104">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="c75ca-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="c75ca-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" Usage="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException (message, inner)" />
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
        <param name="message"><span data-ttu-id="c75ca-106">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="c75ca-106">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="c75ca-107">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="c75ca-107">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="c75ca-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="c75ca-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>