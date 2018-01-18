<Type Name="IWithAppSettings&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAppSettings&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAppSettings`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="9ae4f-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9ae4f-102">Eine Web-app Definition Phase Appeinstellungen festgelegt werden können.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-102">A web app definition stage allowing app settings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSetting (key As String, value As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="9ae4f-103">Der Schlüssel für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-103">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="9ae4f-104">Der Wert für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-104">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="9ae4f-105">Fügt eine app-Einstellung für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-105">Adds an app setting to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ae4f-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAppSettings (settings As IDictionary(Of String, String)) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="9ae4f-107">Eine Zuordnung von app-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-107">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="9ae4f-108">Gibt an, die app-Einstellungen für die Web-app als eine Karte.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-108">Specifies the app settings for the web app as a  Map.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ae4f-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyAppSetting (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyAppSetting(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithStickyAppSetting(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSetting (key As String, value As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSetting : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="9ae4f-110">Der Schlüssel für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-110">The key for the app setting.</span></span></param>
        <param name="value"><span data-ttu-id="9ae4f-111">Der Wert für die app-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-111">The value for the app setting.</span></span></param>
        <summary>
            <span data-ttu-id="9ae4f-112">Fügt eine app-Einstellung für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-112">Adds an app setting to the web app.</span></span> <span data-ttu-id="9ae4f-113">Diese app-Einstellung wird auch nach einem slotaustausch Bereitstellung ausgetauscht werden.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-113">This app setting will be swapped as well after a deployment slot swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ae4f-114">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyAppSettings (System.Collections.Generic.IDictionary&lt;string,string&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyAppSettings(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithAppSettings`1.WithStickyAppSettings(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyAppSettings (settings As IDictionary(Of String, String)) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyAppSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithAppSettings.WithStickyAppSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="9ae4f-115">Eine Zuordnung von app-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-115">A  Map of app settings.</span></span></param>
        <summary>
            <span data-ttu-id="9ae4f-116">Gibt an, die app-Einstellungen für die Web-app als eine Karte.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-116">Specifies the app settings for the web app as a  Map.</span></span> <span data-ttu-id="9ae4f-117">Diese app-Einstellungen werden auch nach einem slotaustausch Bereitstellung ausgetauscht werden.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-117">These app settings will be swapped as well after a deployment slot swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ae4f-118">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9ae4f-118">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>