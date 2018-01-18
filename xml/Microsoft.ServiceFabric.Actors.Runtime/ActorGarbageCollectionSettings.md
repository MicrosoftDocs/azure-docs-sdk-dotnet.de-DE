<Type Name="ActorGarbageCollectionSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings">
  <TypeSignature Language="C#" Value="public sealed class ActorGarbageCollectionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorGarbageCollectionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorGarbageCollectionSettings" />
  <TypeSignature Language="F#" Value="type ActorGarbageCollectionSettings = class" />
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
            <span data-ttu-id="fd8eb-101">Stellt die Einstellung so konfigurieren Sie die Garbage Collection Verhalten Akteur-Diensts dar.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-101">Represents the setting to configure Garbage Collection behavior of Actor Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorGarbageCollectionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fd8eb-102">Initialisiert eine neue Instanz der Klasse ActorGarbageCollectionSettings mit den Werten für das Eingabeargument.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-102">Initializes a new instance of the ActorGarbageCollectionSettings class with the values of the input argument.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorGarbageCollectionSettings (long idleTimeoutInSeconds, long scanIntervalInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 idleTimeoutInSeconds, int64 scanIntervalInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (idleTimeoutInSeconds As Long, scanIntervalInSeconds As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings : int64 * int64 -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" Usage="new Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings (idleTimeoutInSeconds, scanIntervalInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="idleTimeoutInSeconds" Type="System.Int64" />
        <Parameter Name="scanIntervalInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="idleTimeoutInSeconds"><span data-ttu-id="fd8eb-103">Zeitintervall bis zum Ablaufen Garbage Sammeln von einem Akteur aus der nicht verwenden.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-103">Time interval to wait before garbage collecting an actor which is not in use.</span></span></param>
        <param name="scanIntervalInSeconds"><span data-ttu-id="fd8eb-104">Zeitintervall Akteur Garbage Collection-Scan ausführen.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-104">Time interval to run Actor Garbage Collection scan.</span></span></param>
        <summary>
            <span data-ttu-id="fd8eb-105">Initialisiert eine neue Instanz der ActorGarbageCollectionSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-105">Initializes a new instance of the ActorGarbageCollectionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="fd8eb-106">Wenn IdleTimeoutInSeconds kleiner als oder gleich 0 ist.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-106">When idleTimeoutInSeconds is less than or equal to 0.</span></span></para>
          <para><span data-ttu-id="fd8eb-107">Wenn ScanIntervalInSeconds kleiner als oder gleich 0 ist.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-107">When scanIntervalInSeconds is less than or equal to 0.</span></span></para>
          <para><span data-ttu-id="fd8eb-108">Wenn IdleTimeoutInSeconds kleiner als ScanIntervalInSeconds ist.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-108">When idleTimeoutInSeconds is less than scanIntervalInSeconds.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public long IdleTimeoutInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 IdleTimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.IdleTimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdleTimeoutInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInSeconds : int64" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.IdleTimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8eb-109">Ruft das Zeitintervall warten soll, bevor Garbage Sammeln von einem Akteur, der nicht verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-109">Gets the time interval to wait before garbage collecting an actor which is not in use.</span></span>
            </summary>
        <value><span data-ttu-id="fd8eb-110">Das Zeitintervall in <see cref="T:System.Int64" /> warten, bevor Garbage Sammeln von einem Akteur aus dem nicht verwenden.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-110">The time interval in <see cref="T:System.Int64" /> to wait before garbage collecting an actor which is not in use.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScanIntervalInSeconds">
      <MemberSignature Language="C#" Value="public long ScanIntervalInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScanIntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.ScanIntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScanIntervalInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.ScanIntervalInSeconds : int64" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings.ScanIntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fd8eb-111">Ruft das Zeitintervall, Akteur Garbage Collection durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-111">Gets the time interval to run Actor Garbage Collection scan.</span></span>
            </summary>
        <value><span data-ttu-id="fd8eb-112">Das Zeitintervall in <see cref="T:System.Int64" /> Akteur Garbage Collection-Scan ausführen.</span><span class="sxs-lookup"><span data-stu-id="fd8eb-112">The time interval in <see cref="T:System.Int64" /> to run Actor Garbage Collection scan.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>