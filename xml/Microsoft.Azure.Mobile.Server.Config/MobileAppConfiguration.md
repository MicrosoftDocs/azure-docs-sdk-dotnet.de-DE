<Type Name="MobileAppConfiguration" FullName="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration">
  <TypeSignature Language="C#" Value="public class MobileAppConfiguration : Microsoft.Azure.Mobile.Server.Config.AppConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileAppConfiguration extends Microsoft.Azure.Mobile.Server.Config.AppConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppConfiguration&#xA;Inherits AppConfiguration" />
  <TypeSignature Language="F#" Value="type MobileAppConfiguration = class&#xA;    inherit AppConfiguration" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Config.AppConfiguration</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="87803-101">Konfiguriert den angegebenen <see cref="T:System.Web.Http.HttpConfiguration" /> mit Einstellungen, die von Azure-Mobile-Apps verwendet.</span><span class="sxs-lookup"><span data-stu-id="87803-101">Configures the specified <see cref="T:System.Web.Http.HttpConfiguration" /> with settings used by Azure Mobile Apps.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87803-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87803-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddBaseRouteExclusion">
      <MemberSignature Language="C#" Value="public void AddBaseRouteExclusion (string exclusion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddBaseRouteExclusion(string exclusion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.AddBaseRouteExclusion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddBaseRouteExclusion (exclusion As String)" />
      <MemberSignature Language="F#" Value="member this.AddBaseRouteExclusion : string -&gt; unit" Usage="mobileAppConfiguration.AddBaseRouteExclusion exclusion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exclusion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exclusion"><span data-ttu-id="87803-103">Der Controllername die Route ausgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="87803-103">The controller name to exclude from the route.</span></span> <span data-ttu-id="87803-104">Verwenden Sie keine "Controller" am Ende der Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="87803-104">Do not include 'Controller' at the end of the string.</span></span></param>
        <summary>
            <span data-ttu-id="87803-105">Fügt eine Controllernamen für die Standardroute des ausgeschlossen werden "api / {Controller} / {Id}".</span><span class="sxs-lookup"><span data-stu-id="87803-105">Adds a controller name to be excluded from the default route of 'api/{controller}/{id}'.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public override void ApplyTo (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyTo(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ApplyTo (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="override this.ApplyTo : System.Web.Http.HttpConfiguration -&gt; unit" Usage="mobileAppConfiguration.ApplyTo config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="MapApiControllers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration MapApiControllers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration MapApiControllers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.MapApiControllers" />
      <MemberSignature Language="VB.NET" Value="Public Function MapApiControllers () As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="member this.MapApiControllers : unit -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="mobileAppConfiguration.MapApiControllers " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87803-106">Ordnet alle Domänencontroller mit der <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" /> auf die routenvorlage "api / {Controller} / {Id}".</span><span class="sxs-lookup"><span data-stu-id="87803-106">Maps all controllers with the <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" /> to the route template "api/{controller}/{id}".</span></span>
            </summary>
        <returns><span data-ttu-id="87803-107">Der aktuelle <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="87803-107">The current <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithMobileAppControllerConfigProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithMobileAppControllerConfigProvider (Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithMobileAppControllerConfigProvider(class Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.WithMobileAppControllerConfigProvider(Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMobileAppControllerConfigProvider (provider As IMobileAppControllerConfigProvider) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="member this.WithMobileAppControllerConfigProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="mobileAppConfiguration.WithMobileAppControllerConfigProvider provider" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="87803-108">Der Anbieter zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="87803-108">The provider to register.</span></span></param>
        <summary>
            <span data-ttu-id="87803-109">Registriert das angegebene <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" /> mit der <see cref="T:System.Web.Http.HttpConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="87803-109">Registers the specified <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" /> with the <see cref="T:System.Web.Http.HttpConfiguration" />.</span></span>
            <span data-ttu-id="87803-110">Hiermit können Sie um die Standardkonfiguration für den Controller zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="87803-110">Use this to override the default controller configuration.</span></span>
            </summary>
        <returns><span data-ttu-id="87803-111">Der aktuelle <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span><span class="sxs-lookup"><span data-stu-id="87803-111">The current <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>