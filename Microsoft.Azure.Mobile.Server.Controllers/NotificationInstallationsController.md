<Type Name="NotificationInstallationsController" FullName="Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController">
  <TypeSignature Language="C#" Value="public class NotificationInstallationsController : System.Web.Http.ApiController" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationInstallationsController extends System.Web.Http.ApiController" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationInstallationsController&#xA;Inherits ApiController" />
  <TypeSignature Language="F#" Value="type NotificationInstallationsController = class&#xA;    inherit ApiController" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Web.Http.ApiController</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Mobile.Server.Config.MobileAppController</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d95e4-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController" /> einen Endpunkt für die Verwaltung von Installation Registrierungen für einen Benachrichtigungs-Hub mit diesem Dienst zugeordneten definiert.</span><span class="sxs-lookup"><span data-stu-id="d95e4-101">The <see cref="T:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController" /> defines an endpoint for managing installation registrations for a Notification Hub associated with this service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationInstallationsController ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallation">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; DeleteInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; DeleteInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.DeleteInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteInstallation (installationId As String) As Task(Of HttpResponseMessage)" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallation : string -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="notificationInstallationsController.DeleteInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController/&lt;DeleteInstallation&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="d95e4-102">Die Installations-Id zum Aufheben der Registrierung von Benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="d95e4-102">The installation id to deregister from Notification Hub.</span></span></param>
        <summary>
            <span data-ttu-id="d95e4-103">Ermöglicht das Löschen der angegebenen Installation geräteregistrierung über eine DELETE-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="d95e4-103">Enables the deletion of the specified device installation registration via DELETE request.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="d95e4-104"><see cref="T:System.Net.Http.HttpResponseMessage" />Beschreibt das Ergebnis des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="d95e4-104"><see cref="T:System.Net.Http.HttpResponseMessage" /> describing the result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallationAsync">
      <MemberSignature Language="C#" Value="protected internal virtual System.Threading.Tasks.Task DeleteInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.DeleteInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Function DeleteInstallationAsync (installationId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationInstallationsController.DeleteInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="d95e4-105">Die Installations-Id zu löschen.</span><span class="sxs-lookup"><span data-stu-id="d95e4-105">The installation id to delete.</span></span></param>
        <summary>
            <span data-ttu-id="d95e4-106">Ruft die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="d95e4-106">Invokes the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> delete operation.</span></span>
            </summary>
        <returns><span data-ttu-id="d95e4-107">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d95e4-107">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="protected override void Initialize (System.Web.Http.Controllers.HttpControllerContext controllerContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Initialize(class System.Web.Http.Controllers.HttpControllerContext controllerContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.Initialize(System.Web.Http.Controllers.HttpControllerContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Initialize (controllerContext As HttpControllerContext)" />
      <MemberSignature Language="F#" Value="override this.Initialize : System.Web.Http.Controllers.HttpControllerContext -&gt; unit" Usage="notificationInstallationsController.Initialize controllerContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerContext" Type="System.Web.Http.Controllers.HttpControllerContext" />
      </Parameters>
      <Docs>
        <param name="controllerContext">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutInstallation">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; PutInstallation (string installationId, Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation notificationInstallation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; PutInstallation(string installationId, class Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation notificationInstallation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.PutInstallation(System.String,Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation)" />
      <MemberSignature Language="F#" Value="member this.PutInstallation : string * Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="notificationInstallationsController.PutInstallation (installationId, notificationInstallation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController/&lt;PutInstallation&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="notificationInstallation" Type="Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="d95e4-108">Die Installations-Id für das Registrieren oder zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d95e4-108">The installation id to register or modify.</span></span></param>
        <param name="notificationInstallation"><span data-ttu-id="d95e4-109">Das zu registrierende <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d95e4-109">The <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.NotificationInstallation" /> object to register.</span></span></param>
        <summary>
            <span data-ttu-id="d95e4-110">Ermöglicht die Registrierung einer Geräteinstallation für Pushbenachrichtigungen über PUT-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="d95e4-110">Enables the registration of a device installation for push notifications via PUT request.</span></span>
            <span data-ttu-id="d95e4-111">Wenn "installationid" angegebenen auf den benachrichtigungs-Hub nicht vorhanden ist, wird eine neue Installation erstellt und registriert.</span><span class="sxs-lookup"><span data-stu-id="d95e4-111">If the specified installationId does not exist on the notification hub, a new installation is created and registered.</span></span>
            <span data-ttu-id="d95e4-112">"Installationid" angegebenen bereits vorhanden ist, wird die Installation geändert.</span><span class="sxs-lookup"><span data-stu-id="d95e4-112">If the specified installationId already exists, the installation is modified.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="d95e4-113"><see cref="T:System.Net.Http.HttpResponseMessage" />Beschreibt das Ergebnis des Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="d95e4-113"><see cref="T:System.Net.Http.HttpResponseMessage" /> describing the result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertInstallationAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task UpsertInstallationAsync (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task UpsertInstallationAsync(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController.UpsertInstallationAsync(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="abstract member UpsertInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task&#xA;override this.UpsertInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task" Usage="notificationInstallationsController.UpsertInstallationAsync installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", Justification="Upsert is in our vocabulary.", MessageId="Upsert")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.NotificationInstallationsController/&lt;UpsertInstallationAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation"><span data-ttu-id="d95e4-114">Die <see cref="T:Microsoft.Azure.NotificationHubs.Installation" /> erstellt oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="d95e4-114">The <see cref="T:Microsoft.Azure.NotificationHubs.Installation" /> to create or update.</span></span></param>
        <summary>
            <span data-ttu-id="d95e4-115">Ruft die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Vorgang erstellen/aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d95e4-115">Invokes the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> create/update operation.</span></span>
            </summary>
        <returns><span data-ttu-id="d95e4-116">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d95e4-116">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>