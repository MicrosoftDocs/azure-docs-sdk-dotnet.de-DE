<Type Name="IWithAppSettings&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAppSettings&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppSettings`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAppSettings(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithAppSettings&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="d0d64-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="d0d64-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d0d64-102">Eine Web-app aktualisieren Phase Appeinstellungen festgelegt werden können.</span><span class="sxs-lookup"><span data-stu-id="d0d64-102">A web app update stage allowing app settings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSetting (key As String, value As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0d64-103">Der Schlüssel für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="d0d64-103">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="d0d64-104">Der Wert für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="d0d64-104">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-105">Fügt eine app-Einstellung für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0d64-105">Adds an app setting to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-106">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-106">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettings (settings As IDictionary(Of String, String)) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="d0d64-107">Eine Zuordnung von app-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="d0d64-107">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-108">Gibt an, die app-Einstellungen für die Web-app als eine Karte.</span><span class="sxs-lookup"><span data-stu-id="d0d64-108">Specifies the app settings for the web app as a  Map.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-109">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-109">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettingStickiness">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAppSettingStickiness (string key, bool sticky);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAppSettingStickiness(string key, bool sticky) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithAppSettingStickiness(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettingStickiness (key As String, sticky As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettingStickiness : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettingStickiness (key, sticky)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="sticky" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0d64-110">Der Schlüssel für die app-Einstellung, um Klebrigkeit zu ändern.</span><span class="sxs-lookup"><span data-stu-id="d0d64-110">The key of the app setting to change stickiness.</span></span></param>
        <param name="sticky"><span data-ttu-id="d0d64-111">"True", wenn die app-Einstellung in das Einschubfach während einen Austausch sticks.</span><span class="sxs-lookup"><span data-stu-id="d0d64-111">True if the app setting sticks to the slot during a swap.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-112">Ändert die Klebrigkeit einer app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="d0d64-112">Changes the stickiness of an app setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-113">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-113">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutAppSetting (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutAppSetting(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithoutAppSetting(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAppSetting (key As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutAppSetting : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithoutAppSetting key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0d64-114">Der Schlüssel des app-Einstellung zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="d0d64-114">The key of the app setting to remove.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-115">Entfernt eine app-Einstellung von Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0d64-115">Removes an app setting from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-116">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-116">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithStickyAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSetting (key As String, value As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0d64-117">Der Schlüssel für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="d0d64-117">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="d0d64-118">Der Wert für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="d0d64-118">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-119">Fügt eine app-Einstellung für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0d64-119">Adds an app setting to the web app.</span></span> <span data-ttu-id="d0d64-120">Diese app-Einstellung, die bei einem Austausch an den Slot verbleibt.</span><span class="sxs-lookup"><span data-stu-id="d0d64-120">This app setting will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-121">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-121">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithAppSettings`1.WithStickyAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSettings (settings As IDictionary(Of String, String)) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="d0d64-122">Eine Zuordnung von app-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="d0d64-122">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="d0d64-123">Gibt an, die app-Einstellungen für die Web-app als eine Karte.</span><span class="sxs-lookup"><span data-stu-id="d0d64-123">Specifies the app settings for the web app as a  Map.</span></span> <span data-ttu-id="d0d64-124">Diese app-Einstellungen, die bei einem Austausch an den Slot verbleibt.</span><span class="sxs-lookup"><span data-stu-id="d0d64-124">These app settings will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0d64-125">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="d0d64-125">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>