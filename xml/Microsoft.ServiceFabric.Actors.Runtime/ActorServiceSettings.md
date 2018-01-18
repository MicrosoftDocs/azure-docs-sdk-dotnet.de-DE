<Type Name="ActorServiceSettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings">
  <TypeSignature Language="C#" Value="public sealed class ActorServiceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorServiceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorServiceSettings" />
  <TypeSignature Language="F#" Value="type ActorServiceSettings = class" />
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
            <span data-ttu-id="8376d-101">Einstellungen zum Verhalten Akteur-Diensts konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="8376d-101">Settings to configures behavior of Actor Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8376d-102">Initialisiert eine neue Instanz der ActorServiceSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8376d-102">Initializes a new instance of the ActorServiceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorConcurrencySettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings ActorConcurrencySettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings ActorConcurrencySettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorConcurrencySettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorConcurrencySettings As ActorConcurrencySettings" />
      <MemberSignature Language="F#" Value="member this.ActorConcurrencySettings : Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorConcurrencySettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8376d-103">Ruft ab oder legt die Einstellungen so konfigurieren Sie die Basis aktivieren Concurrency Sperre für Akteure fest.</span><span class="sxs-lookup"><span data-stu-id="8376d-103">Gets or sets settings to configure the turn based concurrency lock for actors.</span></span>
            </summary>
        <value>
          <span data-ttu-id="8376d-104"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />für die der Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8376d-104"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" /> for the Actor Service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorGarbageCollectionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings ActorGarbageCollectionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings ActorGarbageCollectionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorGarbageCollectionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorGarbageCollectionSettings As ActorGarbageCollectionSettings" />
      <MemberSignature Language="F#" Value="member this.ActorGarbageCollectionSettings : Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ActorGarbageCollectionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8376d-105">Ruft ab, oder legt ihn fest Garbage Collection-Einstellungen für den Dienst Akteur.</span><span class="sxs-lookup"><span data-stu-id="8376d-105">Gets or sets garbage collection settings for the Actor service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="8376d-106"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" />für die der Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8376d-106"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorGarbageCollectionSettings" /> for the Actor Service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReminderSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings ReminderSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings ReminderSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ReminderSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ReminderSettings As ReminderSettings" />
      <MemberSignature Language="F#" Value="member this.ReminderSettings : Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings.ReminderSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8376d-107">Abrufen oder Festlegen der Einstellungen zum Konfigurieren des Verhaltens von Erinnerungen.</span><span class="sxs-lookup"><span data-stu-id="8376d-107">Gets or sets settings to configure behavior of reminders.</span></span>
            </summary>
        <value>
          <span data-ttu-id="8376d-108"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings" />für die der Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="8376d-108"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ReminderSettings" /> for the Actor Service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>